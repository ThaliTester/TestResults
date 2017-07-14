#### Test 113351851ac4367c_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6CB83554-5220-4172-BBED-67F466744728/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/6CB83554-5220-4172-BBED-67F466744728/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app"
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851ac4367c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61160"
,(lldb)     command script import "/tmp/6CB83554-5220-4172-BBED-67F466744728/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
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
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:38:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A51EF8E9-6D61-4C23-BF87-3CD1253C2DE1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A51EF8E9-6D61-4C23-BF87-3CD1253C2DE1
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:232D150C-D356-459D-B620-81245B7F1C6A
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCor,e] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:633FD0E1-2F3A-4DA3-B323-76A2A68E720F
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onP,ort:errorHandler:) Peer(uuid: "C3F88F96-363F-48D8-9D52-F8E767CA26D3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C3F88F96-363F-48D8-9D52-F8E767CA26D3
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C3F88F96-363F-48D8-9D52-F8E767CA26D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C3F88F96-363F-48D8-9D52-F8E767CA26D3", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-14 12:38:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.684929966926575
,2017-07-14 12:38:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-14 12:38:58 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C3F88F96-363F-48D8-9D52-F8E767CA26D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C3F88F96-363F-48D8-9D52-F8E767CA26D3", generation: 0)
,2017-07-14 12:39:02 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 12:39:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 12:39:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 12:39:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 12:39:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 12:39:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 12:39:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 12:39:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 12:39:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 12:39:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 12:39:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 12:39:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 12:39:06 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 12:39:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 12:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-14 12:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
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
,2017-07-14 12:39:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
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
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
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
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
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
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21311B59-79AE-42C1-9F2A-F71BCB276B34
,[ThaliCore] Browser.startListening
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:39:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:39:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9FC70EED-F819-4254-9FD6-EE7F68C62219
[ThaliCore] Browser.startListening
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:39:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "17852873-B4CC-480E-B160-AAE676A6FDF3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:17852873-B4CC-480E-B160-AAE676A6FDF3
2017-07-14 1,2:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:39:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:39:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-14 12:39:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE01AFB8-D0A9-4C9B-8341-02C7B659588A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AE01AFB8-D0A9-4C9B-8341-02C7B659588A
2017-07-14 1,2:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE01AFB8-D0A9-4C9B-8341-02C7B659588A", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:AE01AFB8-D0A9-4C9B-8341-02C7B659588A
2017-07-14 12:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 12:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:39:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:,39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Sho,u,ld be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:40:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D768C9AD-0186-4DCA-B627-720F1CFF507B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D768C9AD-0186-4DCA-B627-720F1CFF507B
2017-07-14 1,2:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FD7CC7C5-A1B0-4188-AB40-54A208567D9C
[Thali,C,ore] Browser.startListening
2017-07-14 12:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EBFCCF03-A21B-4FC3-AD11-14753B232823:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EBFCCF03-A21B-4FC3-AD11-14753B232823", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C925756-E54C-43A8-85BF-9E1651BC74ED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C925756-E54C-43A8-85BF-9E1651BC74ED", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,12:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:40:29 - INFO thaliMobile: 'Filtered out discoveryAdv,ertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0D72AE22-FA55-4054-B2AE-210720329C10
2017-07-14 1,2:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser,.init(serviceType:foundPeer:lostPeer:) peer:8AAD9A3E-939A-4A26-B19E-1F26CF192571
[ThaliCore] Browser.startListening
2017-07-14 12:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":,true}'
2017-07-14 12:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskI,dToSecret":null,"networkType":null}})'
2017-07-14 12:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAC774EE-985F-4EB8-98CB-836275DBB8DB","generation":0}'
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CAC774EE-985F-4EB8-98CB-836275DBB8DB (syncValue: xNqHVvnc5IkAUjMjkqWxDPNLuFepVuvK)'
,2017-07-14 12:40:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381534BF-0A7C-4DD9-BB76-E7FC86950E7A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381534BF-0A7C-4DD9-BB76-E7FC86950E7A", generation: 0)
,2017-07-14 12:40:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"381534BF-0A7C-4DD9-BB76-E7FC86950E7A","generation":0}'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DBB085BB-4E90-4,045-A376-4108412178F3
[ThaliCore] Advertiser: session connected Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.sess,ion(_:peer:didChange:) peer:DBB085BB-4E90-4045-A376-4108412178F3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D72AE22-FA55-4054-B2AE-210720329C10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50395
,2017-07-14 12:40:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xNqHVvnc5IkAUjMjkqWxDPNLuFepVuvK","error":null,"portNumber":50395}'
,2017-07-14 12:40:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xNqHVvnc5IkAUjMjkqWxDPNLuFepVuvK', error: 'null', listeningPort: '50395''
,2017-07-14 12:40:36 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DBB085BB-4E90-4045-A376-4108412178F3
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBB085BB-4E90-4045-A376-4108412178F3 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBB085BB-4E90-4045-A376-4108412178F3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0D72AE22-FA55-4054-B2AE-210720329C10", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
2017-07-14 12:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DBB085BB-4E90-4045-A376-4108412178F3
[ThaliCore] AdvertiserRelay.deinit
[Th,aliCore] Session.deinit peer:DBB085BB-4E90-4045-A376-4108412178F3
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50395
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC774EE-985F-4EB8-98CB-836275DBB8DB:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CAC774EE-985F-4EB8-98CB-836275DBB8DB", generation: 0)
,# setup
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DBC05482-D5B6-4F51-A692-E8C2855F7F2F
2017-07-14 1,2:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:18F8B334-CA3B-4F8D-9B49-5E164A8197FE
[ThaliCore] Browser.startListening
2017-07-14 12:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 12:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBC05482-D5B6-4F51-A692-E8C2855F7F2F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
2017-07-14 12:40:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4AAB776C-211D-47ED-BBDD-F924EF51954D","generation":0}'
2017-07-14 12:40:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4AAB776C-211D-47ED-BBDD-F924EF51954D, (syncValue: kB4K28XOy87cm360nHsrl8Y1HHtTSewN)'
2017-07-14 12:40:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5A79CA8-4B6D-42E9,-A632-564AB2A52DDA:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 12:40:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA
[ThaliCore] Advertiser: session connected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50399
,2017-07-14 12:40:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kB4K28XOy87cm360nHsrl8Y1HHtTSewN","error":null,"portNumber":50399}'
,2017-07-14 12:40:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kB4K28XOy87cm360nHsrl8Y1HHtTSewN', error: 'null', listeningPort: '50399''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA
[ThaliCore] Session.startOutputStream(with:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Connecting to the localhost:50399
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50399
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-14 12:40:42 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,ok 104 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
[ThaliCore] Advertiser: session connected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
[ThaliCore] Session.startOutputStream(with:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-14 12:40:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:40:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:40:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCED68A6-B186-489D-8C70-DAA9CAE7C8CA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "DBC05482-D5B6-4F51-A692-E8C2855F7F2F", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:2A15EA3D-07F0-4C9B-BCB0-EAF858D5FCFA
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:4AAB776C-211D-47ED-BBDD-F924EF51954D
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50399
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AAB776C-211D-47ED-BBDD-F924EF51954D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4AAB776C-211D-47ED-BBDD-F924EF51954D", generation: 0)
,# setup
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:40:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:40:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:40:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:FCF21A84-2512-4267-BF7A-293E7CDC55CD
[ThaliCore] Browser.startListening
,2017-07-14 12:40:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:40:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
2017-07-14 12:40:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","generation":0}'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B5A79CA8-4B6D-42E9-A632-564AB2A52DDA, (syncValue: OMd3nAOIuM2aqAPq5DMpjnGDx5WNhfYS)'
2017-07-14 12:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
2017-07-14 12:40:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99ECCC86-6352-4B09-8204-FA460094AD9F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
,2017-07-14 12:40:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"99ECCC86-6352-4B09-8204-FA460094AD9F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B5A79CA8-4B6D-42E9-A632-564AB2A52DDA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B5A79CA8-4B6D-42E9-A632-564AB2A52DDA", genera,tion: 0)
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OMd3nAOIuM2aqAPq5DMpjnGDx5WNhfYS","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'OMd3nAOIuM2aqAPq5DMpjnGDx5WNhfYS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 12:40:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B5A79CA8-4B6D-42E9-A632-564AB2A52DDA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:40:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A4807DE-B800-467B-855C-24982A72E20C (syncValue: 2YfbN5S,sU6CUUxnTmbUV5vK5BnoEZkB0)'
2017-07-14 12:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A4807DE-B800-467B-855C-24982A72E20,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
[ThaliCore] Advertiser: session connected Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,[ThaliCore] Session.startOutputStream(with:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50408
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
[ThaliCore] Session.s,tartOutputStream(with:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,2017-07-14 12:40:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2YfbN5SsU6CUUxnTmbUV5vK5BnoEZkB0","error":null,"portNumber":50408}'
2017-07-14 12:40:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2,YfbN5SsU6CUUxnTmbUV5vK5BnoEZkB0', error: 'null', listeningPort: '50408''
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Connecting to the localhost:50408
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
[ThaliCore] Session.startOutputStream(with:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
Connecting to the localhost:50408
Connecting to the localhost:50408
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
Connected to the localhost:50408
,Connected to the localhost:50408
,Connected to the localhost:50408
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 4, 5, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 4, 5, 6, 7, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
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
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 112 got the same data back
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,eamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCl,ient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 6, 7, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 12:40:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 6, 7, 9]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 6, 7]
,ok 113 got the same data back
,ok 114 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,2017-07-14 12:41:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,2017-07-14 12:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9A4807DE-B800-467B-855C-24982A72E20C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50408
[ThaliCore] Session.disconnect() peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D131BF9A-C3B7-4266-80FA-0A8E3B2B40CE", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:D2157855-2EF0-4AE0-96DA-6B541B5D560A
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:794CF4E2-DF66-4642-B5B9-3D4ACD297C95
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6AF9FEE5-E74E-4700-A046-E538896949E1
[ThaliCore] Browser.startListening
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
2017-07-14 12:41:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","generation":0}'
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A4807DE-B800-467B-855C-24982A72E20C (syncValue: j4ZmGGn1uPVGwDxivpbpezSYg0qMzHzo)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99ECCC86-6352-4B09-8204-FA460094AD9F:0
2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:,sessionNotConnected:) Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserRelay.init(session:generation:crea,teVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:41:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"99ECCC86-6352-4B09-8204-FA460094AD9F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,2017-07-14 12:41:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:794CF4E2-DF66-4642-B5B9-3D4ACD297C95:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
2017-07-14 12:41:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD9E51BC-9FE1-45FD-9E88-E6A08077A58D","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:99ECCC86-6352-4B09-8204-FA460094AD9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "99ECCC86-6352-4B09-8204-FA460094AD9F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A4807DE-B800-467B-855C-24982A72E20C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", genera,tion: 0)
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j4ZmGGn1uPVGwDxivpbpezSYg0qMzHzo","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'j4ZmGGn1uPVGwDxivpbpezSYg0qMzHzo', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"9A4807DE-B800-467B-855C-24982A72E20C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 12:41:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A4807DE-B800-467B-855C-24982A72E20C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D (syncValue: uPGSglE,kmaiGpkbPS7jxb1BcFvYHqywk)'
2017-07-14 12:41:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9A4807DE-B800-467B-855C-24982A72E20C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9A4807DE-B800-467B-855C-24982A72E20C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50423
,2017-07-14 12:41:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uPGSglEkmaiGpkbPS7jxb1BcFvYHqywk","error":null,"portNumber":50423}'
,2017-07-14 12:41:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uPGSglEkmaiGpkbPS7jxb1BcFvYHqywk', error: 'null', listeningPort: '50423''
,Connecting to the localhost:50423
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 7, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50423
,2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 12:41:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 7]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socke,t error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 119 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
[ThaliCore] Advertiser: session connected Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
,[ThaliCore] Session.session(_:peer:didChange:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
[ThaliCore] Session.startOutputStream(with:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 7, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 12:41:15 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 7]
,2017-07-14 12:41:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50423
[ThaliCore] Session.disconnect() peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] TCPListener.socketDid,Disconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "794CF4E2-DF66-4642-B5B9-3D4ACD297C95", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:93D8A46B-C1D0-4FFD-A0B5-358048326D9F
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:05F6B8F2-51F6-437E-B02A-47E24E1B1558
,2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9426A85-721E-4F30-B627-0E906DB0F182
[ThaliCore] Browser.startList,ening
2017-07-14 12:41:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:41:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD9E51BC-9FE1-45FD-9E88-E6A08077A58D","generation":0}'
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD9E51BC-9FE1-45FD-9E88-E6A08077A58D, (syncValue: 3ZGzuodSi2Giko3vPTmvONUJnvQ9EiX3)'
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD9E51BC-9FE1-,4,5FD-9E88-E6A08077A58D:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 12:41:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
2017-07-14 12:41:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
,2017-07-14 12:41:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:05F6B8F2-51F6-437E-B02A-47E24E1B1558:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0)
[ThaliCore] Session.disconnect() peer:FD9E51BC-9FE,1-45FD-9E88-E6A08077A58D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:FD9E51BC-9FE1-45FD-9E88-E6A08077A58D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FD9E51BC-9FE1-45FD-9E88-E6A08077A58D", genera,tion: 0)
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3ZGzuodSi2Giko3vPTmvONUJnvQ9EiX3","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '3ZGzuodSi2Giko3vPTmvONUJnvQ9EiX3', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"FD9E51BC-9FE1-45FD-9E88-E6A08077A58D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 12:41:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FD9E51BC-9FE1-45FD-9E88-E6A08077A58D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D (syncValue: gPYMBuw,BHW2N9IYwzs9g2KaJDWnsZcrg)'
2017-07-14 12:41:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
[ThaliCore] Advertiser: session connected Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:27B2CA8B-3D18-4D1B-BBCA-23DEE,60C715D:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gPYMBuwBHW2N9IYwzs9g2KaJDWnsZcrg","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:41:27 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'gPYMBuwBHW2N9IYwzs9g2KaJDWnsZcrg', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8ABBC275-0A33-4834-8930-987F8EE3835A (syncValue: dZXPhAjypA3cTgqXmKmMfp1yxws9Bw3b)'
,2017-07-14 12:41:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
[ThaliCore] Session.startOutputStream(with:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 7, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server received all data: 5wnoOiY2Oc93FHzGhbF6vTi0O6gU9PxwULWSUfDmzEC0MqoLgkodmwNDYIcEfSYl6V5o4cSAFsNbe8HEtiaqMaiIHxMxUCz5EAPiupl43wdsg55dzL3GKvhIi5Wm0OAEZayCjbXz0qlHu5kP6HzJa6k1SB622pqETXF3yzfoyFnCgZgU9r,jDXgBvx9HWVIHbVd7GCtH8XHb1lwD0MEABSfnsQJDSQ0t3c2hBYejtTUHOih5YRwqZTZK18PYYsRZT4leAFFDKyn8ijJTh7m3dexJsJwgTwMJ3mjOKCR15wgci8EVY6mFd9WfkCb8tCbqiy3qGwsVOkAP2dAkJcbkHBnBSQAX44heZkDZtdgYHxQSMUcV9MCU4ndGIzAHAKdHXmExMWS25IEOuWX81lTPcCXcABtGry2TWIFFVfWs0KwWPzDqbInshnBayUAutZjrNuypJ3LZjY2ynAmeT8uu4QBbL91QgGYthEJmW5m34T7RK1Ydohq7jAnY0L9Nt2ssfwBuWScmu7Z7pyeBupiQ9I9PE6VYqnKKBhjzZUf5xUR6QCMQEOJKG1YLbjjxDUaDjVYx2PWJZUP3MuqKN9bzuln6D0HGkRq153NhtmCiX7JJB9PiAr17Elk9e0ZixiH4lBtQJ02NDwvPDpWYz3n3H4uStBIjIryyOjn8ZNiZ9F4UJY5mz9B,XeRCqpElH9NSvByq2wKXN6lSvyhmCf0sYRQScSkFg0XEDy1pl8kGMvxTxgkSv1vKGi3hpgPXKEatA5klcs53gN7KUTPILRZvyULI4jfPCuFq2CP00gliKX4jpzulBhIX9ZZfgaYdlP3IlKWzCxcEehqDYlT6kGvMjXlT9oK9tzuAxLvlEQJdxSPEimKoNYZMQ4bFIEiVHeQDaPhSweFq0dy1nSiwI4L2FBhtfDfxLf3a5wXA6RaCP1oOgdzJIPE5,tpgU4HtukfFk2hXSTeiGg0Rvue2mgmTkmNq9aGL7EAlWMB9wLLxQFvi79WrBS0C6HNDy0cnikG0OoOmJ3gTCIxHSDlBbhDzBqThRQjUEfpdMjJeNTDs8vjuzoQj6BWzSAA68BLKPLdaCPNPwopLr0BrzVHgJDnfHLiFCDkYV3IjxifkoYeHKFufSK4oENCZmo2dof7GF473HxCfn5zrnIZsgygY39a3D2MSXVmEUHidz92K9epOK1pCAmWPKTkHXCCy0Q0fnmniOELlL2C339mUnnsJyFKnSwl79SXPAbfqTryOmJi2GmRYl98eEeH4y2fCAylXOQAZuCrZLqPNHvM8W1mGwG0AP0CX7cpJZECpunbnhj2WtQceqyiC11sUrUsqKoDfqtBA9NegDSD38ew1oZcExVmy9vEVMj5V3eRavhEjjc4VzVAWFZGFV3pEMsIoJgth5UF5bIkv4dh26QYgemyS7iX0JLXt3ILcTh5LpjRwNySwV4wC9SrtAJQnd,2zqgHCG6YGHPiPacWKnltPY7IIGBphKjMOv3OTp3zpkz0agPQ9kJ8eCATh0Cx1zOZ1MOR2ePNeAgtJlFKsvX7Sf7vKNdXPRUXb7k3ADxMCW1HQLhvI96PTctGBn14p8HoszPD2nu9HM7wCBGpmCduL2aIUkyJDg5S8pV65zpYWWMjNk7IDVzjJDPnQp0deJNEXBlVvxK7RKFyxAZSR8PArfAAZoovuqLXLudi2d9UhPvxxMdhb9gw2JSnmklPB0p,6MgJoYfMUYvLVjgMWAaSOBD7s1jts6oNoA1vfZfWJczEguLuhAIEAAGT5BCWlZlICcSentwiOYhVNqSLpqipztqRuxxgJsboyxpEWoREk6WVGFNIWNon1l6EdmfL36vSGsSfWZ0JdIQv6jXSmGkUzzPsSRVQZ3BZVargjhM0mdrE2odi6WnXKi7eIr1vk0Y98NJmUWPhIU4mH0KQlW66k7m9oqmGdBlPr8XQASAQhXITTwz4chxANKaLJgILBnl8tQDVCSEeygaiQg1XUYe29lyVS3sWdYrEHGobr3kJ61Pv6DUxjPoiRAQxwKlgZCGOI4Sma61UzulUh4h542mIiJIT4ViwyqkIIy8ECbsL4ulAEn2snwQGIUBb4qZ4pdZsbjAhBA2v6HQajOmmoHm6B4IqZhzDRT9z5aAkwFiIAisFEmT9TSSbsh9fBwFjgQBUB1EGk0DHTdni9pLmhBWMJmNxEicijohe7WmE0hIntD0HdkFFubZUDiB7u3xNwqbs,dy5BShmjOGovkGVyxHi090OqUJxUoEau2ccAkLmPZD1KL2M3DWAkI2yCUSuypmbqqfisZ8TaLg98iqHINfuFNdudc8hbESNwPbQ8MxjrBAT9xQRxsbURnYfUnPCyZuRyWs9adpWwmQvzMtOpHbxrkX1HXvx48yAelUMFHLwIL9ODidavMGzESHPoTgDytp5cvlIgW1O2zRVXpcPBNLbCYhsRMQmcelUSEyT5ElD0aSZVp5HlzOqL5UPRGch1uZSq,aIZ4QVnjQjSQ7AOHyLXjzOJU0rYNktgVLfzPnTSTYNSgg1TfjHfwBOWngpfeufFRvAFuJkPoiYH6NzPGjd1kBibbQ8phMfpQyrBjtzUGkZoiHw35uaMsCX0FaAYwClZuWImuoeTbYqBx96JwFVQK8Nmwt2mhJ67fra6iO5FEae2QxMf1XpBBC9wofMQh9PL375ZzMc31Shmrupo6FOvcEKLjevjZYK8CiuGQ1JbdtMqIlYVIYIQU49ZiBLfqG1MU,evoVSimFHzkLCZVwbAGdFo9wRNffTZ8TUSfJxG9KvluyeZaBGO0vY1a6s8P6JaW04WugR4NMsrekMxVnz4MdYqRn0sgAY05P2NWLY8D8zwbX29G6ogO2v9i8RhqWqu2eKapq9kulAf0Ii9zsWevJ2AOzfcR0C1Dzmc99BWpTVBivDlOv0tCTAfKzc3yEf5RwfJ6TlRxhnARpWH2P2EMUaKVVnp6e5d63ngAZWjRs4mMcQHBGjHdyHZPf5Lb0jHtn,1bgwpJ4j7xditOF6Z3nADdvebp9hHn8Gnm1KgIjyMWz6uTaZqt3Atp7eOYDVgyBP1DWhLoWRH778kA65nLNCGIA6xkEz5zdyv23Ry6NfCXfo4ZfBZcZolRXZ5h188WpTlCI2gVqyKy7jPK6bcc7GxW9M52AoYDpacngNqAAinXt2prBTLpDSJRJIS5IZSziSXxOkVBtxyg298y2PPUWHHcAZEhpAgIxVLFCMmESshtaXL8LKPvi4UPcWmq744oFV,Hxs5qj5uAXX65UXnr3aAkw7veEmDh1brB8bEt00UKSWsKI2Q5z8yYaBaQRuRaHhGsW7maYsM1p2IhQ9jSzUze17S0q2DEBqamQBJRwBZMzH9Hiu196AgvxZePOaKQPFeqRykpWHUdUL7cjgVwK897mDh2V26slnDD3BsfgAuPHMMs088yxJXAkUN0jmg8yGDRsmiWaWnpPz28ljcq0rPImBtiixlfiKUZ9Mryp76rxuGKkcscjr5v6ClWIBacFeb,1fW3Wb4TFODJzQESZyirlcj8jgWrsxRqIXCA4TYvkVEBkmtL9U1qvwboVR2NTaLHkIykgTPthghE1H0tH7TQqsZNrkxQG0WPX3jUVRogreHupcH7aTCDCHnYPhyp5EvenWtEfp1RJNuVi4w6o5CVv120O318tlSvGPjNwNluhY3orxM4wTZm0U2FGgHRw9by0tnhVieZXexabLjECapE3aP0BTVYa5JoEq7VzR8MChKi7qQeMZXO4sqGp9oIUz8r,MBrdW0cqMRaOpnYyD5tonqL04Iiu1WP1lHEbvBMiX8HALyT0lZmJiduAnlkW7qKz9I067i0ZsSEIcRvfaKbq8WX0HBL6X8OMZvXoaAKFPxAFNZDjoPFOWZ8rbtBRGoSdNJDSkLfKeeLh5NwrojV1JGE9tblad6RsJisG83o9chkSZUcEudBQzSeVaSyCHfDRdvc4gEWWZ1sf9SI5g0dWiAJCJLvQ5jzKHZjlWXPU96hDoKmzswYKwKWED12WO5gj,pxTxvQtxnBGEhTRIVIHB4lxldsOVtDPunEQv3BESBzGitkBwbVx61TTztH7SZSOf8sr3QAwpsS1iJzRan9VDq0f5eMchKJ2va63dyfxjk9zTg8YjCZ9uXAO4uFFQ3GdrL68Q60BAwfVdDgRwyGOOEJKuQ0weSQ1RRmRqZPncLRQw8KEvpLQEvTHDrdMkE9jl7icob2xuBNi5qbXdtOx7tWGWt6pvjYbJ3J21Wuvus0FyY45TfiR876Za2ak2ZoNp,bqdXtYhuXwrlJeCMOU3L0rlVC8S1wuPaVuEs7ALzBoxDzhnqGeWvQBRISQUQDoEhkj4mKFo8KTRZZuFipd2WmOkMYsu5ibNBxxAXkcxRGPa7lVyznojTHDP9epJA5e9GbVVInRhVndvdmotNFN59ND4T3dncVxNEK7x3aZxfCfqjmLXNyXG1aVIO1VPrfWZKfIRf8jxZtEiB36fsBPsgOrIrEe2cjNtM0E4dpZ8uFENcA7wmgoUErVQAoo29PPjF,whWt8YoYNp8QkdpoZDBxbOqGYJcgUg5j9mcsZpgpQJvasWATQ3yZSZOtEZQZk2YxHVlxsKPbN3czoDi9fiE0LG6rw2sezk5VoAfU6ZbxnevMxwLfMCZA2uamiEu9C5ht4LaLGOezbA1A716rYgDqvPxxicmFyGKfwr83mO2S1GBvEDZiPGOOHDk92PSYomzKDtCxYiBn0ENU7McoCG1yALOH5xT6VanYCMizP0f8nkD9GuU7zTMGLC0vxdrUOAGz,E80afcr7SzVGwfD1CzWKIEeZsoYskcBcNXhTSUql1fMZGZImyHBK73pEpCr9TzaL0oe66N33NhmdW4ZYZBcszvzPaZp1gtRhTKrlqgTKlV9VZ0SZqi6Jsla0xY2Z0JbX71tX1GxrL2wyOp24SBPU8CHWt9KbPK3UZaZC9DQp3gR68zskr2ubu9U9vkBayAZGzYzfmxUwMDaphovQWU4edj8ES4myB4OFc5mpGjREo2NVHZOLpVTrhXbhCs8w05cx,ypRvG4FV1xuo7mTQ7ittLqF1uNaIkTqxpfbhiEkzZGp5wJfxO7a2IwiV4u83oIAhBqD26bqJ2FGjX8JQI8AFiCcrqPezGLJ03ZDHsdYggBxYFFjhRlPKRAbkakolqWlOj5i8nvJzDIVe5vOYYxyt6XBEMii5Uzlf7XuZX3KmOORqu30JpsYvpREEB2xpD2aNBRztWyiD2Z64d2u00oUaEgS3tEZdwKQG8UZZp4ibyiFCshcLf9L1f6qqD8kGdDN5,3PLHaIBOFfE6lvk63DjnUhIeIkKfKbcE9bxFN5EuskVS9xBqRfbV0QvgcgTaqaBG2zR8NiHozEiDYltttG4ILldHBtrskedx7qtr4xCRP2oy7iwnUul22SR2ud9YVpXpyz85IOFNIEVPBFhGaadH6pT5iRzdgCLvyHjnEJmEJgjOsHZnyBF2fAcxZAV8G6wBrHDNL055cwyllzwkkLBt8JhzAxaLUq3zk7EZRHCb39mnXtSQlu6HuIoAV76EoXm9,V2zJVxU5l6P2HNLzmwseQZdTNh8nAUWPJU4uzVcWqlpZvQtIFSmKWxt89Szednq9HcMpZI40FdYXlxQxpi7rJV5VHiLGTpkP3t4bHeWom4a8R1MaImj2uKweHewU2jgj7DgojITpFfaEe1VRG8EuOL21E3tySxqnKcNaqhFELPrI6G2vSNxJNi147bTnQYaIhhWp9vGmewN1jmUXQCvQvFHHqQiwg0JUFVczvgIVjoy0ztWuXOnR5NOuDB8NMeRw,6v5t36kqystO6TgjaTc3S4bPIJtOtNJtfe1JQ7G3HY7xLCHON1Js9lY5FYeRmi8xYgrDX78dC4KBoSNTIyJHHb2k8nQq5z8G6oghs0WEDXmbBcPzVdDbv4jskSJa6wqEEIgjEWu5VdopPZHPGV0UsdngslWukjUHM213PNf7HnwhlMJLPr6ThF52zn6NhRuVe10hQ8RLXu2d9Zt1MBvnikrNuJQWZnmKGK1oq0LfKofsBCRstSJ4Db65uWLUJAim,QqAMsy94WwZMOpeLetsVSAQJ4wDcwMuROxsGI0zIYVFN3vzOGj9TaeU26fkHYB8kPP8fHHtTBCIhSpLO1yO94twyTrQrGmicaua4WGnCgGpHaqbe83vsJCyFBcsUZRLzrf1FG7dNIsUb5jX37B522FgMu3DhrcO4ZMc14pP0vMomW9gzcBB98PpLNoBWNyuL2goqrV0e7qjcJpOGZSyCU48TaNNGBHqPXl8XQuZXNU3gFgMGLkew6EihUA7VFEHd,l9j9Fcapi5posoy9M83rt8A7Vp3UdZ3umuC2zSINpAegkWZV7s2kICknXh02xXBfvvVqeL7Jz4YB5OOKTFQZ6GMwiqc92N4XJKUrgYvJPuu8Xlb9SEZHOGKtlnvkDDirEWDsmHLLJjzCmpejli4f4SJ9PEe0K0HAfcPqqsi7oTCmYyNPwaSKcwO09gEiJJxU8p9R5mJXf89rR6UQocMDSZPvs2bpOy1GkyVDspbOM70SfIADtVGgKCUtY2hrLwVm,CtFx2Sc1WfxkUSGdvmPJWrcGQOxzMHnQEz1uBAzNCZjyeOgLpMKaVa7guUHJpSsCS3Q8kRcyfG14TmqpIhrucZIcP6q8JSar1tS4w70GGQKU1K5UGLZn359qa8vuBNU8WP145CVEBPEGqzbkTd4zWZi8WHYVyafTma1v4Zpsdj5FO3DFVZXIWkS9QwuNN1I1DxMK8mOtpg6Km40j54aNG8rDcbiWz7ATvjfPb2EBM2w0josEyf1Usi1qgWVewlM9,kf2rIYUIemXgPfQwoflULPtH6swCScNY1wyvB2SbFCzhesejoHGBMQreUnw2ZXhy0bmSBeuU4nTD2I1DhEt38oZzY7upO1AMR2sRitzN9mwx4js7dnKyIO3ixrnCL5ujwEjiDexoRuIvNU1tEXHiy1bNZhBodNAQuE0Zs7DJga7NKuOlz6AIH6gUpCMjvfGTRcTUv2fzoiR9S7eUC7zST1aIhSJ2IZtRQ8JSpFvwjIbwnG2DcnHJdeOVTtkws7kt,FSAVNyRb31K8WAT4M609uz1Q1trHWvigfs4Op6UU1SDtmRUiRUEjTgn5ocgxJs42CbKaLYsdCGsgWFh0mPYdpzVVZbrbVZ8ZwP5N7S7NfKpu0PgDISLx25WZHKYBK5GlKVPTvcfH4bzjApBfJIG0d8XsjOoimxeAKL1Z9sVllTAZVAQFX8oPtyRhzz8vzmopccqIqWpB40G8hI6J5Con2LswSL4m9Ci7yfBkrOr35MuPohNcv5oYqc99EbkA7XKP,zedrLYB8dAE0bcB9jZvvE9zQGzmTp0nzANVDsa0tglvWlcc5GUNuk59oXzfCft1O972NCFS7j19hyhr5bqhOUaR5zucA0tl8kcpgTpu096sqZb1uZcPf1p9vSx288J4hVFSP5ZgJFt6lM8Ye3xgY9XvAMAgeG53wqcmKLP65lDkS1p6ZKDuB4OfdiIgTghSuUNbA7ClESdjLEuYcbDC2CEokesjiSRE8idZNDWctdDwz6KtykFFypIhhpKUJZAtT,ElbKXZPQ8xPwn96Vnclm01KR0gaNQNcD4ZzPcz1mog8J9iJigGzG0dAjqcAmBHIFogV2g0Cx7DfXbIeppx6zSit7vuSXteYoNcbfrQw0VezWhZU1hL78nkXZbatB6uwCF9JBpZ08MkYmIi3umzt8SZZn7FzzmhrCIdUi0Do1WX4q4nZu4AbhXe96QPUJ8d20GOBCRod91q7ccbwSCrOAiwuKBKoQQqZ6iCixgKMQ1pyRGf6qcd4sjqlNiRnC9Lbf,CrdA9dkG2q82hDn5Rs7rEOu5nUgaaH81OaoAhtEIyfZlxlu3FnTD0xW8GgYiziXAiI2cHh7UlA1XtkivZRnr5XoJa3Qe9WvIrgLXotQmPiMt8ujlVgSXckvH1yS7wbf6J2kk1glMrH13dPDpScKR4ZGWRJIZMCTm1Mpyyuwmm941ynKB5NN6i45lVHmyAcBFgQmBm2tFTd8bwPqHXFVw8VuqWzrwQWSFoH9G9PCjuEI1vk3W9iuWVejSMxACVbGk,qBlllzZcJDIoxjLbrAcbsUJBdZgmjwfgrZUVGUrbE5dOl5VGJ8LbEWh8f1BuXMpFjknxjVXtPClEnNHkw3N4twShTNl1y8KgHSAZuuG7rMwpHRnlpQAeWhJKKW01l5ScW3g4gb7yzGXpWre5TUZGND4mLRZNdBLq1kk5Vzg2OUg2tHG0WN7insPwsWOkPf6UUMorJfV03SfMJAKXVXz8Wrmf4sveOGLMqORmo66v6O3SUiLa0e6TCAXdbgPhtlCb,pCISdSrQ76PoBx9ESjNStIMOKsDzvDTRB6M7ggDPIU4xv5x8ZkPPDTk2M7yUBrMWrfU8j4BQQ7cIQ80z2R9zsxsVWrFfyoArsLqzFMUdjXZ33Okf52ATTF7bpnU6O8PVKoeaEQ9LDZcVWAOAhN5IF5OGGx2EfOE9T5D0Y9ZDHr75X8OaezsTLNuDLmd6p3yPA1u4qukTiagkp5MN3PQpFdkbbalQhutlrHNoIODHRst7PYPpybuBu664Nmk2T1U6,5dVSwb3MrGx7x3D3LgWXV09Ufxq3L3BNFIJfCA36acC3OFIaOQDNxNSllG5HEpQUmcwtRi9kPIbubyv17MS0bE8bow0V6sfrpZ7tfmxhsbX8N91DtBUjHthyTszK2sg2DW5RrwXo1xyedWvKreHSe5PBhCK0cPO80CvxrogmN6T6qKu6ij1g7jfmVzwZukSX8eLJbPtYW0BTs7PKfE7CCBaCWdocZkCfzO9Ys0EbEsF6RDnktmMGiNm87aG6glgO,Uk93amhhnOKcjHc78yN9EEWvrks9dqsALmHfmyulbhAJgR0M0JtdPYdFJeyzOdqUcormJXPTjSm0WRRrgfXXpc5z6pOG1h9WwujBRklC6wVx3aY3cTeA1CVgXk5CO3TmDXRhR2Dx8qG7zRTxdlDkFWNOZMhToIKtYhGBlmTGRtPILnWBClKuBwIGFtRXtaCgE1j9qt4T77qEchGfqAE1KLhSt9RH3tYMKzYFfuwrtDEvt21UweDdALpVqRKPWXce,0xg6GPn08pAKNcs5olG7zWpwps2dGHIvOTQY4wFPl3Q7lv0PqNeRQ5JMdXnuEnN8UwVqyslaXXwWEdoyvrBtMkqnSRsPUybA2S5VRnfQameZOedGTo6xj3mwR2f9EHUBFY0wO3usOCLEmXeVkmBUNYoRO44RbJr9MmbJH8vc2C3g9LN8zELMFYzvWC4S8L0xVB8krdUIINEGAMW1xtorYYfmejpceC9eXVvgKtYKpjzO84CASyLbcepRRKjX0Sim,T05cAxFbnmxeZaWHJWlKbEPfpJdArXIFzVTp13RR2IZDoZB9LtNoWHyf84OQ9PKBKY9j4dQj70Qwkyjo3R4fI0L4OyprDMG4xYSvPRazUq9wyQfw2iSzEcSVctF5kG8liDdzV0AaeCKcu4QS2x7xT1YTVQ9YUZDvA0fSzda2RZ4IludZEhvI290Xy8ewcKdkMByGn0cRuUvdkDO3BFEHUVUSqo5SQF8gDYwtTNsZqOnrHd86QcHAWtckDpJnZlx6,cdKvrcNEWTGB4a9B4TYZxPCV9UDJbpYSDeLJ5diyYIkxpjEEGFxT0Y5p3FVzqANOqMYNz7Jky8jrAMg0AV9Hre2XumsQj8FMBSNUPJaYbX7WlcfhjHcO235D5NpM8J1ZQiBoWEEPCxI2wGy04Hs1xkjicEBxli0OxokP2gBaSGGB4SpceQ4AxSLqBKacWz9yOeWmeseKJNwewR4TmaetWC0dCeEXouwdXcWSyVdaBChBCAXzVPr0q6bO26rJR2h356ZH2fwU1N9D6vCuLkEvTrRWLR4JZ8U7aR3KZBg7frfAFprGmdscO7BjSwZv8DhQ2psfIocJr4XLQt3GZufkXk74jaLaclSgL8iT2dfpr9fC70frodVa7pTCRpcQMRCSO0BH83ZBbc9ePW6dgj7PFbTf4QRgEhnMbvafpnTctPagmqEEOIeTGVqVYsosSD9PobLSbKq5ngnzoJyY6wCxWllCP91pGOcUDSHzHAiThEzcxA0iyl6337CNO9kXrSZf,autET5VjF7iQhkyiNdPg3HWrY6xmH4PQrHkwmEl2OlellgGZyoVwDr7BfjlRoziD97PAr8d3hO2V2x2ryEJmKuGVP1jmF4dLKMNYgt9ghgaqmOLGQ7ttvbGK33xURsRVzzxu3AXvaBmwQyADu2tWdUWBgiNKc5hP7xDGAuEXiu8f6yUmV6h4MsBBVN5judnsx77aM7pzBXAgzq9XKNJhbWzJXkeHwprYqNilDBYGe1p7lPTadMWxJLGcKSS8P1KQ3gi2qJP9cHOwcR9hOa1tESRqQM4TBrXVzZ3hlowowtoJqbGvPGTGgNz5wtFkiqjFPishb2USuaq7wxslzqHTQu4mWVIuRMwxRjnRJ9ZVOJL0hhL4dv5FCJRBRjNQtv0VGRwE5aiRWrmypVN1vs67HDU32pX2ZLZfFekOc7KsOJbDk8j7E9IkNCpLQhC5mFm5FBbo77oc9jOHermhH3G7649aBnI6QSwJ0ehJZzfqM6gbmYJW0KMI4DXnBLdt7zX0,7Yj8vKdmSF0rI8DA84kDVzJfdFgSFKb4xiLWYlBitzpiiiKAAyq2uljan4vYHKmZJ0VkZ1R3MjUP2jLo7DOzCIDxMDvVuI0BHYCbtUJL5SrZyLYhIK4SzIKO38lUY0tXHqYQC5JQFT42Vy8Rneu1I1JTlpscYxtTPh2M1ws8qpMS46LZKCTnZU02ZlWYQbCoCKwCJJaMH6Ywy27uSOu3VxH9tRwqG2RuDWSb8mfYbrZh3KN6p5O2RhOHNcEShGTB,HNWCDYeaP07ULk6g0zCVtth1u3IdpQZrXo2vivDRAkGvKflwJjA0RGUT5m6O70HPXywjP4ZyZfJkgR0tufumZruAVdg89gObl582PIAXT0lIPYIGkcAapqU4qN0ggEE9Cs9sol1EkeYln670IbgFK3XEHpuD8Wm1uAHqb9oGolyvaZh45cqE4yd2PXtJroyYzpLFf4f9jHxAde6ubdtYvOTFG8uC7EQTmpV5dnNYNVQYMeRz4WY6PPuVm3fpB6xL,PTIK0dUCj4c4iCED3JCE4OX3JnqWG5U5EgSIeNnJr8skc9V9wzlNpU1zoBfoylqN8QthsbiIhBGsRmOfz104AFC9mNGPwJrdZuWz2fVLsk4ECP3HSBYTuHBhAHhebL1EEzsLLCXEU0JMGZ2m6PGCYWReI3GQX1vd0KMVKwPD8DxHVmkCVwhBdifJQKgjARYuHcYsxxx0tP7WUmPbvQkJlZm8g3gCcZvtVVcXN40yQpSWg3Baf99DfqQcCWV6UVJG,LQNOzI0t8485hN0UYs7tqXR6bIowqhfQg0bpo5OVK9DXCNwHVoGpjrtOygOt0tx8zV99xA6z7pBHaAgIQiRXMT1c8E6CyPvFeukcHCwVrsp8w0EH4n85sGjMFQv2wAoOnhETX0pUgy8YAgq2AUhoMB8XvDqsumRWHJzhwUqUqYxEJ4QaBNBu2Dyu3N5drFppZAffaHH0d5zcCka1EsmkZlmpq1tNlNAvcFm8baMsuxQmDYG0tfSrfiqb41DK0nK7,CAaQ4pxFZXd3sovFtCkJsEHoXGiNtkfwhFQim2NMj1ViWb7LPEFoRmyt037eCYeqBaL8ZnN6uS2UlSf4RCoHOxyKw4HDX7yyESkmqEP5JbjHdndDluCH9vMfxo5XxtluuUI3RA0VPhJym9twXuKtqH0mBcIh3LuLPnDVinnBnE5mfedojkuMvykwEfK2XZ1nMseXFNa8mzXyV2E2ctqMJB7NgzwjWquGbi9gEKCsy6f57kf5u5avsqeSLePZ49yM,Cqbt7a58sY1TctfOthHpqicB7EH7F4qkZ0xaN2Dm7gSOsEt4v1gYBvduinI9z57VV53Z1zeiz46tOcB2KzQG9ykXEmrBN2U6uDdyAa2OkAC3NJzXdTm2NFXN01eh84NfNqKQ8fiybWMEgl2ysQnHvbZRdfO6woKKHXNXi1AAy2sP0bauvqKcZakombXo922gA1xPhdU3nDfC6v2DPib5lBg4wKaHSQm2s7vmMtpSEo41ntaO1ysWCGOvIhAJdbBn,FHghtwRDPg6ZNat4DC6YmzUsf1KPiOItSTluCR9wxwkltCbCyVl4dT4iAZSg1N6RCqlg7Uz0gOdygSaldifMykPAcj9rgAJsMp2waZX6Gxg1sOW0q5ea2r0xJ1IOGbREZH5eckyiZciq7amQPyxdboXBzIsQ1RJ2fK2qEjZzjd7oQIOppw7VT9UAQpFDka81fIqPSSoMICIpoqPepnUbfzrNffF1ph4wFkxRYM7qxxuz4BWDHurtnmP9rs33r3Fg,N2S4KK4HoPAEuMciFp8LWNU0ctnhAu4p8kkzI5SfkKvekkJsTEkX5fhx26e0olQvanpkOU0GRb21G51IURsdcyZHBGt1GZI4bYMUuBTDhTVfDD9TDwmL05jPQXTbb8oskbJo14sF2TQTI1VTWSf7dEpDUZ4ltA4ARNDjM8lfeVD5A09Hpqq4AKfYdszdYjtGC5SYZPE48scxaYcV8tQ8828n8ZU4FObVISAWwVnXlamTngG3LcQg2KkdH0ooHYo0,ILk0xNL3n4rHLlJsLdKdcUGdYsL96yy4YGO8cDbmKvcThuDd2R6bNM6WxGvJVGf2tivroiowtXsSROXJk3xWc3bhBjuYMqiF2lkNhLZdLXKpMEdJKNJdf4tRC3Phpul6MiwZFiHRTR0kFXXhsP5SaOakmvJgVk2TtWaE2Soq6LU8dpkLkWnEqWyNTPVjUgZReSXwM4cunh8Q41Xd4yqJAsZt2HsvPouwfnSBh8DuKmcpHXKPIWGc576B7rneIeVC,ridk1DMITPmE515pOrnGeHfOdzYqiXaWDhihPLmqwfXYYabIChqM6eqIqfbzI74On2wlyXRFZYt24vhokNMUA7ZxoFsljj7GvGdVtcUWT1sWc3mlrdPRAHnml5VatiSJhkzkKxPmBYSlvbs2ai5US4f2juClRcAwStS8KRFF1pmkXV66H66arGormEpxUQu8MWtyZ4Hn6FSsFRF6xGiLxDO5aL7sLCNtxedYQ6LOfmiUjv0rAW5JUuVOfZpTgMbr,CuhTGKZpDOqQJ5AR5m07bUqc6mXwOAJF6bDaA3NYcNeidh3M0qj2Nnvm4J97k3CqXjuOu9LxkmLAd9yKeTJlZROYaUhoeADiZu0Ikcenl1zpHVxwAV0OJGx5q9QTTYCEselmYY2qa1K8iR1GeIIh2lInNAc4Lo7O0LhwL9CEoBNflce64IY0VDrY7Cg8BNo73EHusYb7nAaqA79x9mV8S3lazv7VkYnkxyoI4Q8sXoUKFUzcYijuhQwrJCZi4890,bnIgSgEnvcKfknIeBJ3aB1dOrn8gtlsk4lU7p2mYZ2DqydaQ8vvDyMxSN52yaVOCiKnqoK8Md3FktcNncSWKeD6paYyfq1NbAFE6skJ8X8l5XxbbK4nG21YXbEHOKJu8YfBxjlxrwOdMK2rBKxCf9t4xkAJTF9Nvkwc4mjUMveitiTwPrvLajozOX494sAVGQMS9HBnGlIUt6rL6xYWAgkscpItG5w4OGiAOfFZwlvEx23XmY4RtfzfF6xb1tAZK,QpU4N0hwurR8RDLrjun063JcD0n36xvh0Icg23BxO0fHuuRquvsdHNfRvUR9qPmInFz4RIYAee4Wd1083QkgDHyvBwNdwerGhX3dvjSlgMkEcehUxWB7A2r5RZ9z2r2j9531gVPFhEQmbyi48eDDZizU6tqdLhNHDrUySnG9mKWxsq2lGZyNFIUmHTQn1TWUsPiXD1JIwqLnQuGK13LIHeqlI1VZb5ZlnyXlKySJj5sk0Saz1QssON1yHk4rt4Z8,r1y956RICva9orXQ5DbBpxNDqNIP0ac9Oj9Gv37PVWlwJRUgheVdVlEynKl66a0UVrDFqdwQPxrKytYKlV2rfIyaMi9t553KCDqx3Azb9meANfOEGiZqETZGVWWDtXDSy2g1fELWObrAHD2pd3sIh9H80znmcDzM6tMDyM7OB41r3OVxWWTttSbU5EqYjo1MFHfKHxdjMUo20Mcs3UK4O38PIXCMzewMtuwpPm2KmFJd5QazLGktXgNeoFWSzc8M,ZxMZgO4eSmAOUtr9UMWxrLfFYMoqxMMrecZRBJhRDosEGWR6m5Zw7J904Bkst4VXP0Oj0n3hzK1E2BASLpqWzLYo5ENRjTW2h6DXDufTEfTcqcUMzkWAd6Jh0mVOIEnlQcThMHv0reKG9T65uDoTydINZTfKRo4nuvqElHowE3qHg2TotQeQAsYcoUIXSNvqZcNHWLCC3ytyM8tzMdGVFBUyEy7Pj6pPAX1repEzuMGEXm6Vs9XgGOjWnEF0S2U7,slh8FkGNhJCbSokGYbinYJEsPW4fiYocZc80FxVEtS4rgv16mxPFuVmpHZNM5yF1miMlnVnYrcT8U4DZAomUVdkSiCw7t1VkHytSoZRmKC7fvdzDE1gVsaeNRhx7JiQCYyNca4gXiPPH8pagbOSSoowWoW8YmvdszUUUN6bygQE0LcY3WaIKADSzqqzJyZJExaoLiDR5dDnVMi2taqfxCUb2erymmaVYqEkHRLf7N0FJA3Y6DEO2WzakBDw0pVYR,gBlvPHqdsD1EcfJbqva4dcIZybJxmCOaLiXfQhk3V60YB3yvpE13IhSNFFxdDPGfLHqz89D6eeSDrko66qvM788rC9ST53HhaJjEBZZhUSOpDtfFtZg1bBhUa2UNEbMzUqsqpqNxCtUuGfw9lKRwiG6vSwKdTy0aLoeZdqsye6SaOzZim3xz0XxYQ9Y9qJmItN6E57baxO0tEhwpM5WiHFLXUp7yE961d9pCjYviHgv4OW86vEkiEacNA48zSERZ,WQ2oVpyt5wufKrDZHrNLjCAnRsZ8QnojzTXPsf9OkZGgGAGxM7yYnrBhkuSZNUbPf2shHmuXYdHeSKKgLh52yPeliKywAEkf5RMzrg7m3TSU8QXVB1lvnL88LkypuufnbKnh8CfnYzYJ6uBdZ1onXsGhSibJu0S4Ell01Wll6k7114R5p9CLVBltxDq5bVaVMEX40h3iE2d1FLnx0UCVhGr4vaXc4yi7AqwTRocvJZtlVoyxbrbDaKk1OELruC5z,aiC1BSvD7oCYBswUuQN7tEmtpjx0hfuiLWWkr0uQdkXvCCQwvA6kJZso5MqDBRDXTv2UVy3n81xgSRbbp5evSotuRZwnHWG7WCRhUntDaeD3c4IiobVlZFQdYZDCi3aEAtsTentaL2B9xfWyhdhLxZWtRP3EiGV8xpXGt9aAlLTIn7xvZpWVT6ikUBg6y5VMXbvmBZyVRfZXLen23BE8HvESsziw7ixBX7zPAuQCeUCLTxu1euYFf0LHhYTWqxjh,2iDYMPrMh3SQlQzJP6qQ0WnCaMJNSTOhOl9RDzOyIRfzxRx7k4crrnwVn23OckXMhRRNSbJ2Xr4wZwg4hxdg1d7ZeFlJSHDZqW9AWo56x5gfc3udtq5LcaphSAFLcVYllpj39m2a9WvEXx2iPawnaGXPjuipPBXnftBzvYbaQ8V6pHjK2KDapHRlp4fzT9omNEq1LCobLdk6fZu22x8O4k7VkfH7KJtlC7reQ5fpj1nE8pnf8NlaIcmgI7Y6Idcj,u6nml9cXogU5t1VaMWMgarqmm77GVFrNB28sNJIg7DkNs0I1p9peIZ4kIIB8ZptXU4Ffjl8naqcuDoueG0T0cxxyPp4xfGogoBKUTjMO2rcqgGrtle5ACwgGfIFCBdIdUGt06IpXgCRMx5du6KqQlabtFzNmi5JQwiHzcG30q9ZVsqTWWywHUSlEsijncYQsHWo968qAtMUkyKfGXInIkicCtAHb0qr0XEt3gJ3NtNKBf12AJZUY5t2O4L6Xl9x2,yEzNrBaUoQrrtYk6SibhK8uxXNkUEiAsdsnBiLjMQMNepgOKiEfuvaMSCUzPwhbzbTj970VBiVKeJdKwfp2CbzYroYjp0nE5leozQMeu2Wkc0g6iQqgFOPDPtqh11gDCKgmEFiie1MaU5kmbd7l9PxK4AeMb1gQlqEgGKgwiPaRFHSdRAFGm1MnjCSas31XhtJpsAxqevF07NVSki3PMX4ffRZ6CEbonJjzSs7NAAidj6pCqrAM37ha5yRL34axW,bmE39CflMyV341VrzvKSPm9fxlWhXNYkPtuHxM56WuVxHXX7e5IZZ4uvBjYiJpLryJODkEpisuZuQJ775dGg0RJA4ui63KrcO0uKG3PRjchbdNhEvZwfRdTorAyIIsDT0aNB1In81eFGaX4KXQu0HnPZfTUjILFRzsqseY8AqDJ7TBNB3bzEksgrMKSk4IYzQPJx145IYeCDYd5NS2vFwGTu3BHfASmXPCyzvZRdRTD3QWIWlUEUywlpccagzjs1,FPUF4YGtYBNgYydX16k5FqN0oxflXAVHjFsn9agmCENm26mwdg3SzN6zwCHXt5nJWySAjKsLNZpIXMVqS7bQwUP7LS6Q9KDnyWsP4vwX7OsoG6oZbg8C8YKkxUUnJ096UH6BpqYuHGICF2mE9o89fTK8PzBahLRunaQ5F2G1IW8WlvNMGNwzYH3Rgh2q1dHz1PV217gM5T1TnoAkVfqja8CzN710mtQifwA9UODnul6U1skPH008V3kFg3ckzSgB,tELC5neQHS5L5pOiljVkwyUHscC2gHIDK7nuxCPBiJBwJjLTMZkP5edHRruzApbtd9gR7oky8RO1sPoLMNaUcPocKJYtFnSqffKshHAV9Iy3Jl2lLfqcPjyiWWYfToBnLpAgwsebVLQveQ6xjRgxoDmRr6pi35aE5uXEPJd4kmSTJ1gkeJvOpckpayM2dJ07c1jf73OPr2zj2hWrH8nKXwgyljC6GATbW4ooDEhmVUpsFm9RoKqKs6fxACZxLAIX,fxVcqyO8MwUjoslBM8Tlv1Q4e2AHKIAPcuhuY61dxSalTgL8Sop094rkuNep34encvlwrWwPp37YhS6JAbNRdUIYZJo6Hb7LhH9COnr16MNGN8S2wVsUhv0eeCsmsG6bDIK6cnGG6Oq3IUXR0SoGN0sp5TboeJ96eYaoyMcIuS6LQFysXANUioZ8bXr4Psi4jclKmMRQWwPuu2sPvGWtmsTMRFmHVRxn3OxXsegmruPmfgglc5zcJrG1JW8i5txc,PIIViHdrX2nGmaP6V3g7PhIIrQCThc7vLFW89EM0ono8XfonsRfxmi3yhKihQKnV9EGFFWUYt2xiwv4EsiO17PdUwSeRqXoUpsdZaapOKq9QubzkjLZ1Y09dkhkR6HrJtvL2DvxUmgBqjkW9OxaHqQ3jYEPisxRXHZ4VVQeqPpFHLfjxINgel3fhl6h2YsJ6rkaTuUpxwqAQ6BlFndUBEReY6AZgVi364zJVWMZeeIJeF0An7O8Y50mQtfeHFtBG,I2zUERqP1eOvnFAAohpcwJQR2E4hibTRqObdbXph30Tux6yITLYpAuMvoWxtFbHpSBjAX7PE50cpQJT8OdxQDXKodBLU4vfki4lJUY4xELKP1CgX2fmuZZiFbBWxxeug71AzQNncH3VKDDenJ2o4cCH1do9tNDGgAnQj0k6DvV02m9T1x5i63FQpXWL1fa0OyA6AFnzNVfMFxRnqXSmBNoTqBbYDVvaHW9AHxTD2fmTOBMcB0p8V5TAYVXHEfc5w,hSeG9DlaTCwlKCHAJHj5XpdkYbdyE4M8zakCQHqkLA211ddOxYpJiTSX6XmGLItMNoVRkR28Y3shw9309pml4YiPK311bmk7ouZAdQ6fqbgmUimxiWxr7nkcKD2a3rNtlklVLdugArqGVCAow8k798WjI4WHVOXTYqXVIgIw01ZuNR089c3nZV0f2kahqfJfr4bMkKZtahTHvzxhUljLFLQNUN7XA1oTG0g43ZIs8RSU3AAJyNdopPaH0rNpmOLB,x9ntaICbuTwdn2NMVXyi1uK8SdAcJ2kPlxIkjf4VxohXUJJziOKvf72cKLXzTrQyssTnMcbfejoRKPqzyA3DsOI5EiR4gmlgFW8mfQjvBcPeJv5VbiRmoRplt2aWQj64grGY95A5Ao04CkaaphAFS7xfjVAL6KXhhvbdtpT1HxqqYwoFvN12JXRxmduJPBJiEGCsLchHsQM3RbL2BFrvkUgenKS7FGjbDbkTn0bvabLJVc713Pgi0iEKMyliWiL3,YUSNxlPNf0mkXRpFk829uOj5hwb6iAPxasXh8meT28KnbB6kAH6N3rl7oNRR1eQLT45L1AV68KbeNQVmFokYamBhuDhV76gjob6P37WD3KtmoF2SNDl4kIeOp844v4l1nxGuRHCmi7Vg2DSRldPiOUgCPs1x4DHrzcc7V0KSA8WEtorS7jirhiQMiEM752ycbog7A7VDZlH6IZDnZr6UPAnBfA9NcLK0kQVy4Ejjdi7hweGQRke3FKUIbb7zgahu,FCH3taOp5gqjJQAv7eQDt1TMFoS695ZaOJs6K5Jd0eFdtMr0oWJiub5GSsNfhqb6V9WRuwBTz0k9uzzc7qd76VmMU0yD1o6eodAG4ZtnVVPikO10idz6hh8ohkNOabRVOIU1T4pFCnHmZmUwzpQRbPMF0zsyR1nH0kXLWUkJcnH3O94coEPyblW50YVPiukkMd1P9Smmf3CCTevA0nQMbqZtC0fjRQxigyiSLpfRY5uV0T73BpvDbaAUNSeAOCBp,Q3Qd6aWlERUFJdeTVPyzKl0mf91EuKMj5zUqCPxWkAZ5va2gD83kylFjbqdPoF38VtryyD4zb4y1I46EYYlueJ2huhm6MtQIgIOIspNnKGYtwFHu0dSURtCEhdU7YPNHQ1LmTfYW3EnvKp25d6ihOB0qgmjxsc0tcXqvTYs7eSVhKOGCTgYqKjdE3S0pfQg2IPhkWrJ7lUeT4dOHgr6VXzEyGUuasmAgseufvqyTp4DUqQJGtmSkuwX5BVvmyKN8,82m6zQQMO7upTfL3KX9mBNpkgL768Y9o1QDXjYgldR8SfO019xQTDLPK92j0kRaCZCvmZ1IiZLEJigLygykYaGYSCPnIriKyencLY9N5hTZz2BBZ3GonwNOASFUMCqAGhQr1NFNvk12063wph7UNDBafm95qfntBxfizCETHi2XDzMuxXdpXYWzQzEtEJUujm0ttf3WD7tXeXApJT0IiV9uTvLIR0d9sgivL7E79d8ksUOLD7BlVrZ3lGoC9BYhW,ElqBvTOnVUUNi0C6OapnniYjpfX2XUISJGJ1RTyAGuznfDgs6oUyEs5OOfbHJVq7tmkdaGaKlUJjEpiWzWI7sebluODqSsYuMLCMJY1EyTq4CPA5859F3ozPkb571FSC0g24SBJSnmYaaA3fvoraLGd1fZZhH0Sb3jNqg9HGHqTtKQRtbHLUTaQxJ4VH19nf8lrD8FuFXJDaRLS4OfRIDLMzbuMqeYCHcAPxPuEuTXI96kWphDJB6wV5nyFuOFEK,lhoCWSG3EkMWCb5mwthEwnEGnojKSnR99eVnXJHEZrkC5TdF0IlfrbUshr9ENmLsPtZIPUNj9biP8DPIrN5apfBTEu5t5iSntM7HOdaHNt1ekJ15IThD1LdfecwyTlUeNHetedJGymYehYScWlbIun7SoD8ZO4QPdDxGrf3UUv7phHBlUWjh9rvrvQWOOtk2DRYwgyPCU5Cy3TmS2Pbf534qAOLZVUJNe4p8kuEGghuB4b9fJCHjyZLVUSkhxjGu,ohEbUueQwswZ7pDVAxw3zyQzWUGpMHnthyCo4YyQ7KJPhM1OiZbiscPWC3WdFsSSTopVJdKJiv1l6Bk4kohBxMvFEKf4AnGUXqVKusJhkGzj6RSPtuniZRChLeRUjGwtR672pJjmMZPH65WDTy0Ul9zfpUjgv5ZA7cvfZtdPXZlJLLsPofLnakDfcvwaFx640Hy9D43JeRnIAShv1fHI8F79VpQX5FuB8lSgnVGEoioNB3ZJ3PyHxxYDFwKmbPsU,xKVlWKzdEFgek03OAIiW4wJH0gM8F1mBIvIS0WEuURCmTAsXTJxBK3suahxbXy6VDL4qYd9cG0oLvCePvNi9wW10lns675sstTyB9BTzLadzZlIXgqnmTPIN1mugGRQ03spExIxNeKuHOmf3SvtQFGwxYzbJDV6TYmCEAMSXjAWPyJC77gIBUQYsdQXIu6dkGz7d34GuDFYGM1uYcVc9iyEllUWjYQMi98sfIePswjMfH7NHsuBu9CKfRgSZfg4b,pDNbdbXutHw9tGiNtisu3UVu7Rx7oDl35vOcnOFlxCGShkbr3dM6nu34vGEdD4p1cjHP50qo3e4qnidbj5yWfQGSSGSJEjUnCwJu8fPJ8JxCVQ5QQgVlvE7NPGpxdVlNERfYtZoQsDJq87tNoZ5wUHysbD64bqOwBrcGjEvovSvWlyuolQ2gpvfaH52dsC0kUsqjzoAmDcxsqM4UNpRaWwub7rvujvC9UfCLeX2NvJPyLuZ48nKTWW5tNSbBkiad,qXTRUiK8gMnt0KVrjUJVt48Eoi42YYUn8hi34pX7ODD7R5kGHJpY0ARk1UPaaM054xewnFXeqhEJClNDZ3kRyZH2UYng8ywXJ9NCtOHsVfD7RS8cEim6dRY558RA2XcQfX2G635EfvCANynvJY6dQc1kwemyQDwGlSFtK0WebF7MADGCtRJbczFFxpMHIek8h6WUPViUzSwtOAb2gXhRfKK28N023eRY56lPoqo7zLyTK7xGHSk0uIUI93J9Kgoz,vxgtg9lQVIDoIYcoU2yOVPgYG64U6THkq089vslLbj19AQimBumaSUmJxAjIqO69vJjKKeVmrbIz77ClugZULFuPWM9awxVJEmrF0kPRqRmnECm5kbIdSZ9KvGnsHV9DUeUMSIrm0Y3PQfcOvHAFAG74qQnFQEVv5tPLs8T4aH5nKnylTNafwC9OIGuH5SO57IVTHAZsEAKdJ9zQRi2PZHHBkAVxGkktcOSc2FbMMD3RXO80Ss8A9lXYi7dDQTtF,jAsa2CCTrNXzw1EyJZMwDoZQkWn0vTdS0n3ekcxZQF57RmwlbJFoMeXs49jAg9ieoHlc1o7OSqW8Nxdyp6NPTtzlB3DO4pBAUuOBM6FwEs85AqxFVnUo0RuC5meXxZMMIP0k5W9WVIsloBwaNdxP2hkp6vMepGFpRsRvLsobjjOiFdzGF9dumjVLylM2QWQNH6ze4DQobcYGn63iZPQT5wJKhCl651ou0lZAVRvV68l2xog1SHHyQadMPF9dOLap,RdQ87GJBC6TWqcZWj6yhz84SPwz24dTfXrqy85SqNy1BJAttPPkv5P7yGEje2WV2WgfdHh6qxW6CtVbsQ3Di6IEGiOaJqJdJFyJdrkpqkkoUQGLQYu4j4L1xowmWMutyBVBiHdUsiUBOSJ2HOuVlq8xxPY6LcxAiV5tevcKYPHCO45ZEPdecOteSB3TFxJu3Oxeh0H0ZXIwG0nFahj8uk77Xu01coxb0140PTvmvez7ttkFS2fAh0LT3dpRCgp0X,p7wjCYyt7sQYffJkYJoOEJJ8U1p0tbW6yJ47jeseT7AkVinN9Xr40TZLRwBetVcwYcbXR7ZNLYZH1KlcgkDsXssGNFkwOdu0xfIDUKF5b9OVQg3SKJHhcRVQ3WpMhE8NM6XwxpeQt8jQ3pJpX1yHf17ULVNOdAsjNIhC4CSQcRwKccnEuCMdCGNbHaebTj6KyCEheGVNQjNfDaqB4VotWqjog17BS813hdjRrwOxHLgUVsnr6KfPP2WI2lg9nfQg,KD4NNQxmVscale0NOq4ssvoe3K3Q0Oe2RfsPF9VOLKNq7YWFIs0kcXHTbXuXWsm6I1kzvI3NoUXVsWj3QcVR0Ees5eDmgtuYxHVqYyHmA9HWzOCnvvjMWBAunduQ3YS0WhhfO5vZvsyDNDWxuzsCzcKGtk8Mnivv7H8g3jdNKUCZK9CBMnWoSxgVEysVuXWfiZz7jndQyr8J09H5YdDWSkj1NKgv8fl2CYYPp5IRCjLpTpPhTbiL9bxbDR6aXnz2,fUYXSY45OrKeQYu5A5qEPEL1iZkRnMxE5SdI0dNLtZqatnDMDMEaRE0LHhkCrLpTkapPGVvlBVgd29maQ898UfHeSHrisHUGEN3VBTuPYL8hKBfgwKjYzhLpAsWwu3bqIDY561HHDge25TWF8sB4OGfPYQ612hDsvzDatweAqnCqvhEmeq20C8izh1Zzaqa5iqDbKCGjpVgQfA9QH5c5Jc5nbFzB5Wps81Td2LouOzpP9xHubcfw4KD3gqoVIfCP,cxL1yd7n5wHCNfbxdVgXVeAB6ucX8LUI6M5b3UqvhIliQGjaKOqHf2OVEcAlkU9VY0tz2NESwaWc1a58Q3mbKcPiG2EGm4TsGAhzlBOr6mjSafklMvV7W8KCioCWddHCqytIAKc12RMRAdQVwDWZuTw5WeMg1OJZdSOeexAjv5KZplAB6bhAjAdRY3eTziPZ1jlvg0GyTkpHmSBcWZej6I01uMEzpaGD7EuTgQHoHD7Bv1q2AjRUUjl9WGqdpk03,IR15cbbhPeHosZMs04uc092aZxWmIqNSDbl9O3LcytDuwnIOJg2TmWYxo1mr2ONJCbsRfkQRT8wo3JrnvcvzsrRRZGZBK7tPB1JudeK3inbtqzDlK97KT3x7eG7hlJoHYQJvyAmuP9Tih0dxcBk2oxGAYfBeOZjCwIZhzswPLVfD7jytD3STc4ztk6r5gHQqsiS1KBduqZLsPQamMWQF4WtIgXcU9WvNomOXboNLgMscrFPiDisD3XQj4kMukLJ0,FAOL9gl6hsEMqIo9d1oj0zWAPo56ry3NphRPPC1l5OFNp1EQ0Waro98cnJ4DhV53UQkdkSodk7TLGAbA2oFnyJYplUzlqokoHWyZKvXlUHEgjaLJEkQjklWBtJD4Xe00LugEF4NuFwok8BpOgd0iOxy5gDPMqcILAUJZ97O0o6aYZpVfZu4wmY03BR70GQHBUwW3PC0B0DrxZiJN9No1kXO0wzTTvjc0c2bSPptc2dKHaKA3wuyV6BVzxswrQwrR,RcucNpg70mVDsRnp7iKep6BzaVy1zpPggNokg0HST5PCBPuyZoR25xxnvO40XKJvC93EzpMT3xBMCpbRIb061u8FSlBUB7EXoZT4vYW1fcJKMW2AFKOBjl3AwuacJwuVbkGaMMJ7eqbO2PcYC3qFIHsBnwQrnA4WRKsoOwV8anNvAS3zQoQBRg54hs95uOdlYVyr7u9Vs48t7vJozqQs6yG6ylsKQp0gRal45u0YRWKYmSYwKiSPfXRTl1xd19CA,9eQGXXMcQmzPX9wbgu9KOlkSgiWm6FzSHWDTm29lamv86zebA6KcqJWZhPpOQHt7VGpmx3sg6Ao9xbGMPXo2PK1QjXQO1oWgimPhxppKjlOYLY3Va9AU41X4jo4pWPGjARzwRUxDtugvrX8cYJuZeqvHRu4x3Zlt9QUpXjBGLjBPCnmmyRFp3JVNB1EZBwEB35arFkxTcXLkDbXIljQFWNhvT0XOc9VXIo1iaoTHHEEffCKXZBW3z0WqzliNQAVj,n0DL1COYZtDAku3YF8GydlxZ30pwnTrhs4Oh8iA4Vy2UMsON8whXiEX4nQRFnxReqZnnwqF5sBglPx5YVhBr7K6YOOvV34z7bFIaWUwVuC9WJyLPHBCft79YcWPV9s0BdP01xRh3L8kLJVvBDWanb8y9FfDw46YbSNU8ElYSave1Ch6izd8Pq4JTiXVvSbulGcZB6oKdjZvhvAbGIiCCQoKPYsP1Hz51DxUUWCenbcOa7Ur2Ifv2UxQP9thYbHMb,zDhfM1qD3wi1rC8qIhLVzVGiD2yVni6e2Hdb225SFAzhnfCKuea99LjLtBcdXSyWVbbDCZW09d5koCHaEUHOaFjIg4bb49bonRxsKwFAPKkuJytnNSW9HfREr2AZ2lUhqPAuJtuHSau8I3Ed6cfz0MCC4j0Cfk9n138j7mjrDO6xw6k4f93Y1ffSrxVJgnoGk14soeHoXBLxwR2e0EL6NnbvvY5WQKayNLnlNXLSoVxX1x12VpOaJ1Kl1xGGHfVN,pSP34j6moWzRRPie4QY6XJBrMpXKmNGnKiZEaGwCUm3LvYouBSP0BRM66RDwVcKftYXU30nIvpmOxR9xGIEyZhr0PrLhFAhIs86Cb3elyH4rL12xH9aiMeXAxX0CtjjY4sOmvKiznGabM7prbzFrV8pUNzQGm7Xx5boK5yry46cmDB9Blm29NyQ6xUnDY4qoPKDyzPZW86ZbpMw85geGWkHge7MziQADCslG7GxKpkddCZrbZQ3SZeOofHFBecwS,bgFsbKS9RDdl0nJDBcntO40IvBB2rgvw02vr10xPeBOIAlqTyl5rAXyOhzBub6DvB1B1NBMcte6XbhClybzN54eQF0ty2NTrLJ0zRtdU4HmwQ2gybJiDrIs8pW2tYTHbQ6dT9qs2I4OkF0ZgzvowxWfiDCIpzA8Aqn4wK4JvBDJtuK5tnepGXhyUtqU8QZ9Kw7scLX6iMnwI1x4fKrjgTHD0PauipX3lD18L8DU8Ozg2dJrRpovDjYS82ZzLCYhg,DtlfGHtryWCuopyB7G8HEh8kqnQ22x0yv9gqxiWneSFBCBWoYjOL44DdMv3WeLgnkJJlBTtyn7Wjc1wsU6TrNhwWSWask1jWml3HXLxgDoTXx2i0jAgUDRMPTgTboWh54s60kFnNJC5IyCeEWVSK2neXhfDgZ6lkYuZMwyYATUrPbw7p2kgIbToPVNLSjYPtSa4gH5pG8crVhNSDKQZpp7pNbBzs4Y7dARsTXCcuuN6a9luKOyRSAVe0xuCe8bc1,swZMgkDkGLgG1O3ByJejZeeChQRw5pmJISxuobiCuunvh06TUFYaEZwUiydrZ2dLepZK70IxzPkI6oaRprWYgA4I80S8yUFzxK3JWxCz2WavmyCxrMRmd32WWnk6f7sGa06M8YBY5Q0UjqwjyeDixIDCgYbYESugEDPMNwFqxjO7x58Q5wEmRRkcDpUnDre8BKwEOoCX7azrzKKAXvznkDS9KwSSqXegh98yVdQ5Y417Fk6ENZaq7wvydTHm1hZW,0rhtIuTnpyC0k4NjgE8N2EnnRfpb2ahKYkHTNm77tItoBzfkoebGJD2pcogzHbFYqvuEGyPsxYY39lMMQBFpgd2Xi50gMthVMwkz3MudaYHpqvOXYWhjsJPCKAUBLN4P4RJbylnnlD2BgzO8Uxti0quJ3toEBglR7qnoVqNSXoWvOZ7WYTNQB9SKuLrDyZ8LuHQ7epkRiMxZvaRHePpggn0UL1qehog3uTFPMfMc3YZgafqiGPBpps2NC6thFeF0,tEuZeHxb2At5LFESA1HojoGdnJYQUD0Ar3Y34psjrb5sYoE7Vp7RiHbKm1557jPU42338lIlZPPJvXW6pYR44R1mqRKy9VTbaQNta8Jrd8uoDynhBic01lnO7BD2xItrTSDzlBF6a8Z7Q4DmrWXRpeZb3G1pIV1yV80smwRo2qvnk5VB1hgvPmqdSttCft02msBdO9LLp0jGrNYPNIPoyUnh3tneFVuXMfzHGm7hq4UNp5sdS7MzTVzoRWFiCavE,RofxpDOphCi0hmAXccBKk2FA4qpgjvLceg0BL1cpY5zYnV7uYfGbtx0vQMCz8KaNYFbjoTUGMGRQuF9Krkj1cR6lwp08JJxiMFks9j56P10G8whkusjcgAl7Y4bdYmEvBBQ9Jr6U3fOSZOwH038wLPbgeGgu9Ntm6cjS2cQvTf2C266bDVsNlXVxDQ661NtzxE6nQrkUJS1uzUqFcVCEWkAXBhapuRkpCE2C2GmKHZdHBOybxlfE4xlJlLPoybcw,0A0vE6DuCLHrAjp8b1JkwIoPLOlJJURt3e8wAdEdTCHVLgqWOGqzWadE4nhCGue6ubBUxOyl2oi3m4BzWbSSwD9p5vXqREDGn6XJuo4cg9QDzxFJUrEAPyda6hHhbxPyZEKMpGC3Zhas2D78F6VB3PDdwCuoS0NX5qGn9dua2N6mWSTr8UeptTmuVpzEmw6ZHZf53DZH4UVmTTKcZ0Uw3j6U4jCVoVLgU7by3HhbIow7CwFLFuZwo9mDQO1XLe9w,qoBNJPMBSBl4anBaNHKgHqEAe4d9bOxJF1Svz9S0Ht3QxkGtHqDJybY6fYLe2tKl6KOGBY7cXLLa0xYK3JGS0382tHNztYlDy28WT1Lc2xX53lRYjvfxIERnvHiFDCSA15IPOyCSEhWhPfNPpd8v8gxGbevOkAm4NxbNnaNKog3qVGxl95BPsY1mooS0oBsLkWKWCJ7Gvjk0jBtpNSa00XOB0rlRoL4eFMRsP7JdWwOg1ngVFGb0znnUhglkoTC5,kpjQ9ymeCAaQMwOJGrOn5tqpM3sjDAYxdAkqmYDdP07L2HtdgZIbJCVIXGr7MALS7NX51Mnn5xqXLDOSAqSw0QRwoNDjlsgXVmVIUHNeUr8ylu73Qqox82mGsevBDwJV08MCoXOsgtSAFD3mE4dQbpaGbcBNtTdamSDcqhxyrPQzzWSeANAbyPd8wgrEEjFTaYeABmVerfVzuOb27yWvTdQ5TjzDYmzqcqVHbLwOrYfbYKxLwwSAgviaeTVMkQy2,aGVGknmI62QRc7jiLuMXQWIpRPU4eoR7DFpMQ4gWODMp7D3tfFM7eL6YfZHh0YieuuTghJMyWfU6gCaMFPXuvaAukYzKoG9dKo4qTTKEcWMwjSPsgW95iFCixNM4TmV8bANCwU0FvEJP7QdnrNGC5wrtpcMtAVi1B3x4JIuAY0HzZoILDsJDS7eceW31Fm39Vwmm8B1GnjmOi96n8SHTu6JLgfNgQwOFPr0NCHuPwcpKyauxqqT6NMNMDNdq0xFM,uj5pE6ukTeaVTweeGkEN83EhamQ72b30tjtb910w1nc2zqewwhPzLwuO90uPZfr6eWBeAs2OPAx78G5WBLTv95P0sGbwhQ6SyYZe0IXOLxG5aH8sCITyZ1hJtmpYKJIKKQbhKFIXTDFh6zGAau5dzwg8ok5EcOdWO53KIoVauPl1YTefkZ91qDc3xz8ny2zVOPaO06aOhb9JodhP88XG6VIXbF2FSlEav1CJQhOE8644PuoDSQ9sxLgKXBJE2Wl2,IHcKmcNPgR6RgRtlFw96yJpDB60lyLhZ7aJBWI758FEaQKWyf26Oejfn6NAlP4krVg0xfpYeBv6xQPoHoK4fyTgMZcJFejSCOjw0uE7QtOYIYzwzauIxxTvTwz1TRZWhqNbdMtnFZJo6vKNxIpha5O9dGIHtyFdeKxrvmeBcVDJs4DpOZtElPzGzm6oC1LMQZnc53rkUTkVRo63lLZUbY6rewjTM9n5t3d5Tem1DBGzpcInc1cCuPR5RFJwNRyyD,VwpOSw3V4FonvRhVHsanmzISW9xjkzTs7TFQEG5Q0odzqW0glLU32nsgjQYVaYjmt8zNQ0vjo1k9fctxoKpA29GfkzMM8KtjjmzUG8sPFv9kemV4c00Q5CAEp2T0ZehaunMHncqr69NZ9BtHmAlyPxT9hAu0VQBzPoppr745qIE3R6gmctFbi74T0CXIkoXM35mJKbk1fHoFV5MSJoZK6sheMHHnWOvw3nrsTxbDJqOpP7p44O3JTY9VAQ5FOJfi,mfPUUWVfX7Ff2xpy08XYtuXxadtajJeJy3XNEyV5kpRO1eLUMZDn6wWHHCoNct9oxBQ0FYzuRrzzXgWdtGrsY39crkT3jbcNEd964Q3TQLRsXZWIc0Esa0ZpgL2hgVyDLGQ6aymK4sddN2WhU4gIuSbORbJlgI8XQ8oSCWcIhgz1cEKjIdIEpUFbh5gJQZOa7B7InBMpurc4yw7nu7VoxoT8yxhSbXgUITKEhxOvJ2JpX0REtg8fM8xL6PYSvk7s,QIvHqlV4VahmpvrFtw5biVXoKH7Su91TV4TFNzJ6W8mh619Cn0lnAVN1H3gSelAYwZLnds5qkJXSfKiyw3jqkwAluSayRs0LRSLgzJBym8KBh8MgqvTiDIjfmXtMWltWSpumq2muIKAIoOnXVKyzfHw7gw3P6hCYpIGNWHziac2mF7VeJJjzniiUk7tNmqjGtDUth0fyHkecII9EPQxvnBY2maJcOv6DFCxkXaNoDOasZjzdT7UvVYKcycmQDKQ8,8sjE7eZaDRt9lJfmuQOiegV63DBh3Mu9BKWSbx1Jhu3UcjA4nLy3xUkx74iWmI1j4ZkwaHfsadJwAqOAZcvbuB34MRAA1iqHC1S5FUQPcdl36oa1d5lFiVxNQqEa6mVTuTqZTHB1OebAbUEBSoiXyIa54tXvqTum4soYngcRVFlGXuO0PzRivM2f6MhIyhCGnGgbz3moi6JDZqX2cds7h0N8HYOZ5Zayuxab1hULgHljOMaoN6Lm3Dg5TRAzt1fR,mIKTm7L7laJ8t20mSkdwJHsRPZNJtczKJYCv4hIN9xQJduLwHmt3K7AWPjswl5YLW74twzmstKeayf4MwyQgdVHwCWTQPW7gUNFz4kKpoUO0Ii1Ttnoehcx5OCVZqx2RLfHUxmXpqbAOP7zTu3A4ygIrQTVSPMDvOtKqrDO6CuZOtFzTGkldEgZqrWgSx3ZTPlNTjrOhqkYjSdWRtRxfpoHl6F987yjaFNz6BJPfvMjNSs5CTJhyhk7lAwwkkDs2,vYK09NgHTp7WCwTeWaWbOPr3ye7Nl56suk55vc6cJky61K2fo4UHWPJPednXvWNohHJEGfyJ2ED7iHGDYoQJXE4rth8KUCFYT1evNOjShotA5sk0rNvYLsMU7Kts8I7FgOXrYjecyLpL4NoEkXfAGMCOofoqVzJB184U0yPD7b35zieYAe3L8ZMYQ9qIwI2n3V7ZS9zNLrGvX4TgYDMr7TqHBhBDlngNXzs2kFCeFd4APhZOUnuY88ODoc53HzSM,fOimo25CL1jox6V3p3Rdt7i6N2qp2JiyGFBktCUMFnXdLCE3daSBmzGbI2jzBw690btei3cFoWD0drmL3k59G6cinKOqmSej8IrCgddxN4shAdDYxXhiHYLcx4TfNyNEOwfsDfmQB97hDBepNWVMxRA3Y7Q1ztmyaTJXMb5pozgIF7h6ZVBuEEgnhDoDVEh7H4LV1ZNA87WOcV3EMT2C7U6vSRt8IeQ8rDhwpZX7ugd8JhAudDpsJwASF12tU1nL,Ax6hinoqfmLJ4mYsbnlLTJFGj54H4ufNACFVNL0U2UalHVAlwsPlMGKPpmZeqKK53dEwqqEeub3trrH4Sc4aj8joNiREmceQqx7m8Y855SYLFTLT73gPZ7qNqdEn7ocIhqeKAhpGTz4nq8PRG1R7A26CeumR3PIS33DrLnSVPF3lFauhabVzYbR5nwFErF359YGXjgVaCC8VrulcKzWttAc9qAtUHzhEI3oRJ8XkJm1tpQ6Kryct6woEMOCHlsNA,ZeXNKo2PBAB7R88vuNhVxS7xhwhY4ZzKEcFphQp9QqjCGFCFdn2hjKVdStRHZNF5JEdZjMniU57EfrUUWC2n3IgsHa6VO5UX5aKOtlYi8OWxFAnKOJcjqyX0w76XsODpjvlAkFdvJ3HF8Rvq0emYcVaIOcLXUbrfLpnh9tebd40jCTSqdmdxdrHyAuHEIol7E6auGVTxqYPlSQ1cMEIIwM9nEdp1zpneuaOBHo6d7jwfvMe0GB2DpfqZI7BE2HLu,exit3liZQAAMZIWnO2QoVIlkk9kOGp5HdSlT9tN6SHSl2Csl9RC0yC8O0hVAyH6KmuMlAnR8BJHDTC0KEVqklNIhkqxrw01YIwcnSenuPSsF1ABidXymNVde7aSxMEl74PUF7QLyyQaTkJS7CyMtncrpUXz2t1N8IDwIrML3pLeLlD3sspd7NoAwBQEEAbEkwXqq8VIoryV1Crp6MORu30MBBar6xaqHOTocwEDSX8CFwvkV4lomLyGdJuYBsnt7,GAME3T5OzXrOM3Hl9tqRVcKmP5vczXhBYzLzTf1TTzhrvsBqiGSjD2s8PvORCKNis5bOU2cMsBADp2bsXXw2iZu8ymo43FHRxckjUrGcwU8HH4j8yysVOEFwj39TTiQohCis82gRNp3Vfq6DQEGMbJn4xlGz1O4CmwYiz3tKiGUJHk0lHv7ipVX8ECCKZBp5HEA7nTGgjYWeckRz7ZFGBTNQPJ34viYZydDMMRmGd4LrP0iYMuRAxdVYQUFwpSrS,99xkooClwrYwIJWEIyJyHkzjVLiNbHUx9nbOSsocu7OtwUEPwCccBPPVjhxcWt3F6OWOZwQ0BIKyXGGNy0VT31PZFwk69CMEVrNsU4wp3gsfG9jKVnJs4IB2CbdFkxYcLcCqPp1ZfnLso1vGBnkOyhowpLtuhikGBsIO3xHEwHI2GejRyuIORFhRKBf8Bfv5IVbPDrMwfN1CI3DSQHi1udJEJDrQByAejvPduEkIxjIvG7gHioAgjsN1EXyct8mo,FIR1HVQaryMhFNFSz43WldE1Le8rzZYsuzjNsAlYl1Zy8OlcRsJnuAkUIfQb7sJAlhqKSvv9OuE2LeMFZsrpJ6ENNSnMVfjqRjutS4vysc7m6qRRM9JJbzlUgZX4szppgTK1n0u9pAYU4uawdtcLKGPxHAFcrrshatnx7RrowIidrhAMQAqO5mTFsq4BJh5QJqEOl8gKqcyUIltPivxudZtNTTBBadygTVRY82CYDpPbtOmKRvtkzbBmVCaoicHJ,FphOIQ7UBAXt88DF3AaiGhaOorSRBd5Vv1rQqngYqZy2AvWmez7dmGKztKfxDuJlES55z39mEMpkt1xGPNkw9dIOZ5praiFPP67RgsjF04wGHpUBu8ae2tfdoYGzfEwkwLvABOA47gBkR2movbVmnJBeKLY8Vijc25Tq09LkijpqOgNvJ85va4wmWA6sMWA8zr0JWvCD2qj81dUdNmK1ekB6nivm7JPpXEz2fDtItrxiHGkU9yJ8ML29mBTpfyzY,WA7bZ0tqTA34FHM1P7vQfBueYs83XpT9L7dk49DjHJuDqspxBmEciR5TIB8GYvJTAsKgEKFMLroXiHHvYIVY7tTh9kfOxLg29Un85kgFfQ0teL9Dvc5wNYaYnCQZFn1YkVQG8RL48z5xVkYiuylS295ImUsCv3TY0SQcTPWKJ45btzuO0PzQ23hsB5KjopGmnMfW396saWNBnBGNVfvKJwA0cGlecmYlFcuufy5F65vRv31oVMMFcWz9e58hg9Qd,GtMB7w4hk5omEBFhOnWSwZgknPsHJVnoCSWNURG3KNgiENaT3fsCrf06S1aLrcbxacZa94sqFcDGDhCqmdPYER8ql60KZdUu8Be5Sx0EWydW1i7tU6Wn7mEW25qvT9L9ELN1nUuVYAbPOq26wytxnEYRwpfCcaWgoMBYjmXjtaEqUsy2D7ifEoTzDWbJnJSqPRJ9Gpl6bUJJdpUL0FpAgF6vt2ldsskNOpIJ7gozI9CYd84pUBWHLtnkG8Yudmjf,9MKnS3m6OxyhuRJ0lkIlsT19bdPxVGzoU1tsruBrUN0EwoZyGyhJ31u1dzaMU9YVQfyhU7eduTujJGtMS7ZNM4teMF7MMtp1JFIvUkWnFinRPs2RYWpNymHxKgOUsRlhMTcBjHVxoMyeBabcM5xRgfJ8hPY5HAfqBuwfLdPYY5CtzCUvmx0R8WSh58yD7xkUIvMHy4I5p01FxKpGKIWfMB5apuz7jG3wxF44doqEm41nOPyLVVdJuGYSMYns6B0j,jEvjtJKQPckgLr6AqLAQyT321Re4oqhueqgZhNXYR6ZYp1w0DIVDHRj2JmDrO9Qy8ny5P6k72UQmISOnVsmkspB0mo9xMtqOln9mDyyJSiEWUBcqCTzEYdOgxW2QTwZWGM4aUFWJ8ofKpPacpGkaf9OG8QqDl8TvBAFOGZfMuNc09GIgLhqqMdUE8RZ4KGJLMb96vrZezYQc6wXOtI7nbLaj8SR9XFCIFcmsQZAcuT8Rd4RVwP9toqzem2BrGwYY,mZzgnILF1kAo9ePqVaDH78lCxAutsKLtuVi9qDmVQZcQ51nLvd9wEmuN4vbUNazYdfxF7mqxwDvTpGS5jZfgOOC5A52Ja3LrdJ2yHTerKsy7L9uI3xomOEEv3hkOxoh7AzZawKu6lOTrvQT8fdjolh2QzaYBXDKSvcJU15ztrHqmuERwLmCuzCLiZjWtuQ72oWI8lwkyPWh0ZD9jnUKi3jsr8STwohuHiVnZQfj7vjIqKay6H7Admlu20DBqadNY,6enKT5XchRDoRF1juNbCzJ3QywPYars18don4Ke0Bg18Zerd21C9exWHwxjluAcPkpzfVo4d2gXJ97xNZIEXIwPnJ42jOS8NztxTqRgDJnQ7QUQWuCZKjwHTBqCbZmr7SFdd2mk4X0oxCtzPLAfGlhiQ0WBpxYlPbdHCAsv63RTzMeUTmp97uHspTY6qj38kkHvzQAzSBScE3rQLk0hun3YIaBDfNvtqIHE6gQHxEhEcs5JwvuI66FAQrYjzGXJI,xg0qWh2eKmVsWcFtgFYjIVJ8o06IIjCLNlWLI8RuXPPmPr538dcTOyaNXdrUxgovlo1XfkAReUmkfmsd3tCtJIRZ5YrdEIyFqxwLLnZOejjSRWGIW4ZAa58B4TP7UDT3U7x2jRE1jEWG6SXBxjdcntMJ6NpUjgxuKh2L2gyp3xfnqLOEkXKSxvDbk94g0c9Q0oWfRnePeAVxgahUxM16zVdoZJPTrrBJiFReoe4FszpiBIALAmuO7vbSiAbcVr4T,P2u4sFXUQt4GM7FmSNKEq16CgU7cNPsQWiAKXj7M7Nb6wbMqheU7g0tecSl8b7gkD4WPfV71kQW4izHIdt9ZvAR3ssAoj21j3ClSBuuqeFAlMMZc1Ot2NvxDYv3zw4ZtOq9iFe62GqHuHiiRKJsQebx0JcJOZFAS0MXbx6u3xDfyjke7qHzO3D1VyIT4O0T16nSwhtuVbMfDBTOFGG3tf5GF0DLO004oUe3KyMp4k9xukFcuEKkDcHmSaDSm4NVv,s5SHju0HvnQUemTmTEchKIZU03IWOrRBl9ol4FfiyK0no9pF5cJ9ora2OlMKW5CrF4fZwiaNAED3ozXZn9E7raQ2DcPFDf34Ee5H4PyXmZoXxlUDYQ4ZgYhVnuTW4wRychNdYaONr7OhlFzwr3JPGZAbkAbhBCnL2S46pPIqMHqTYLHHBocWNOCZzDSbWBQl1qICv4xJLiw4IUQfCkawn8GuefaLfAtgT0fHPAmJk3lsWmJCNWbcZOdhj9xcnk1M,AwPL3FPDU0VRfdo8iRt9ehIi9sKlHAvAHeFmGeqI6FdO5P5e6ncLDzzfQ3AVDphtTJrqP1W0G3AZh8ZlzmvG8aoEc5jwxDZO356zLFWd3Vy1YqRL1GjLBn2pCiHjZ87tXsB1If1sCVejLnzAcD0VhsJ80Vh7UbvaSKiUvNfVTw4qFmNprLRMBpsdt0xvmsxitKt8OJ6cjyRAJ09cOwjbxERuSGzefldFIHruLCmccRhjRboYYYyQzcQbgGosxmdX,BoxGFeCLeEMHi7PjoBwVnE98BwbYJGQJrrbtKCYYRdGKT9YLGzwpI99VLfrzODLYwYkv9GV8HGecvd5KAAZ0bHQPw24ICYK5hu50SM1nOfNQ3HxbBHFzsZVoqrdWKSyltEvaBRogL37AGSzAIebpO78R6Xb2WUARj4Pk2SjkIsBFouBSJE4G0VVowplS5oSRfcUOu2dpgbnQE2KWiZiMVz1ZmoP3IoFJdiubdMef9bkegvh0fY8zLjbTm4i8jUc0,r8M6j9WNkO5xdtYkF7DDUbPKSrQHPEASpebUWHU9866p0XrpRPpdCmqhwgpQj5I94FAf4FeWcrhfoQEowuJ4mrMQVNxCcjI0ChKFNzTxwY01oTQW0j5KnefFYYbDwV9XFVo0DtoePzEa2l5N7l2TC2r3IgQeNzMvO6VxhGZDOU2MzlNehnGbE8uEIlNsS3fabqu7uLzZMms4XaCcKBstJto5jdRj81gUSkw1Whf1bw7bHCGTVVFuqjhsg7h3nqBj,7L2j6JXYMIkx1rAgyVtcRH53q6bpt8BK0Poc7q1Iis4smdTM6zaA6h2le0G7xniCQHrz0iPc2T9TVHtsYPhMxFILDDN87UtUlgyBZLnaZ4USFgjUWuCXBV3weOCLLTyB5G1fUNwSAu4hTeCxQbDGSjNAky23V6QY20yXEyQeJehZFCoSudaYQMPgxKoN1qoPI4YsSPIPTLhbpBhFLasR0v8pXhMbrPnxDa6UHfmojmI8yOgTMAFchgObV7dVXELm,sBOJH4SocrDTHBTfGsPHdiNqeJgFlFNLIL4VF9V4Tljp8CQ5vvO00CJF3RVnOEraoiCNuZx2VLowLYOC4oAfiZqTLw2bRR0QoYnRqkOgmz3orHhJ0Ok53xDHssEeAwzzwE2iHlaDbSCKaIMxXAbUFyYvKlKsOBaqrNGhLbcTRc3fE4Q3N8dZcqPBBF16b9kVRyOf60UsBtve7eBdaVBOXorsrTkCGFXKi2nyI2hxjdHiNd4nkHMzURvEKZKH3SKS,zmHfpxvQIffK4w9h07bNfKoCM7SNqVH0m0fnXp5IaWv5KSDS3o14iJvEKJk6XOsKNDkI7fwQDx9WCE9qr5UwR7YT4tyRtHNPJzUfXPaWBS5mOdwtmL9SMYzWTFvctYdTxnhcSORdEcwis2JSw17ALZrvV5iHfOD7r5qiPPExedzeAlnPG9F4kLTMR4eHB8hdwUuOCoPnsPVy6jWqD6JZbn8wJ7yVXCxr2nRatpIQc6q4ZJMExXwjqrJYHZrWi5lE,GEi5M4jt37nllnLP6CjGUilotJ4y7yKHYYeJND6bJ9IwONDekGfj8w3plTFAIGOrXiXOf6e9EfzJgi7saGh1g5HkVqBNt4T43WLX4vFhv2tlfI63LxicLf4XbZ4VWFiG6a02M5rn0D2asnZRWpYWKfaxeVyDbU81FMhcz8PeCvzgm2t5H0qdhb3t4GRyKFqxQcrwtcdah1OCvBc51l4EbkieBRbR2WqtnhanPR8V3cNKrSQp82UyZlF09mlYZnQ6,IHgzr2Hjv9xIQ512doTXov03ZyWFYXKTLBfYQR4oBNnoPa6JkLmoL1cxEUJ09dYOWsWG0qthzcKMsS2S9b17lthOtuUAfDjaCdH0xtZjSUvRVqRIx9kowpHy8lH97xZsMgsKP1zcpsKnPmt3ogforePrLaGIgeFfsbGeqaXLzH5GmzRPf6jI0jmxvHeD1xZmkaMKRezd8EFFB8mGRsLNKRyqJOR46aGtqdrE39j0oYwn6lReOZqfx8D8fAVtte6W,wtz9GTEXr7LZIT8BP6l7UajXe9JVQci3D0PMk5MY7dMm9cP2PaXU5VYjdLRRJAC7YCfVeyW2vYcD5lS9KpxLSgvFiJV53UCOBFhCQHvnihwFSkS0k2i4CDM2QWOmPf0fEIMpvBy4BqX3VtTXFyAkGrAlu6nWCCoi5oni14WMbPor1xmnDJKmUHA9Lz36wjXUrPxirxNshehmnYQ5bxdKry2aCIC0HlxbDTpIHpZPhe4WgYOFQEZTgsxn9UZkM3AR,nDLyH1oAw5iAJvjLc7VldFQS4me5qgmKmWCI5KDU5pdQvhwBR93vmHIacApOgBlUUHxp6a7tKD5XGLX6it370KiuWGshF4YV62JUZsVY6z2smiSNXZ6R49coOYxS2axXMhgwYGVKihMnj5xGZJVmi2CTSCI34MrkTADVe98OMsRjjaPga2tflgVkbwhKeUJhMAuxYVK40o4mumtNugMQVhKbbKXev5W0SJYxPtg1YCZug7eGD8jtyI19L99zkr3w,rKH8Vd55BrVLixblEwao7VunDtVV2OToAVpun4X5zGmi3cgSUQ3VANlmbxPOO6NrrCjYNGrfsfXntZtXuCiFvdeH5xckkT0GzELm4uTp632hAnhtPTz4WbaZ9MurO97oYab09wNmKyXkC9WriEmhGoHBw9OSzL948fjlRWWaF9FcLi7Ow5TfG3t23FExkJ3tYvI3JSrg90f6RJUHplcu2ahF7cFADSr4lFhZFyA8D2I1vI8OQZlgK4jUJH8DPnws,6lZejvRzx1wgvyLIUiFymUopFtgTJxPEFW4PRntuBlwcVNgaHImro3XnPNJdJWJNHhNdg7Oko8TNAM0gcgRv4u0klhSg0VbhAjvDFU7kfMgf48j5Y6fPVIwUCUcb8ujm4ts4sESUpm9R4dHUx6R70HYnP6k5S1Gp7K2FImQgVhrlXkpXPNtq6oG2aW8Pu9VJsqd8JjCQfdsb7IyHOSSMDl5LTw5TX1sw6o9CKvB7MMW81ORtsYKYaR58oHYJ28jp,G8Uh1TyeGBsoRjiGN2D6jX8veCHUwqRwO8VLKuijocjzqIjLZyt3dvJNSgYjOTEZcAopcAJL5NwpW0UljrTbAtippPMi6JnFJQfn5B3ysg7E7ywXeC0rP5dVfChqYMXhb2wJji6UnuHCP2KjKL5vbN5pyTsn1gyplNDlceqlQl1RH0LersGK3i7p9Yg1HjLVXzA8Ju8gnaWfkgjJMwuY3tvRxtJ4Q1RybKs8g7NHMXOjr75AqRB3ecCbl3uvxAaa,b7KDvlvACo7etoyVTC9kOugEK1J3Ei1HZAX0fffUzLkXkUR9T80h2FDv1xXuy0b9oUQXOQTviTx8w6BuwyiQkBae5jzkkXHbGY9GrJlTozliwqIBkskTERMThN2scXyui5t4lKzceqAHc9d4GGHEW16AY1OKsN7k1yy9GynprZkzwXuMC0BuBUoJ27jKpPELRbYFgYipRgjALrRz4xYkCpp0cuzlADxI6b4cr7atUkn1PmCknIxE8JXOkD7zWULO,InxwkRkAAlWxnMH5itGEnV4Zs0g6iCITvN9jxDsgyqJYzYuSGfaepjlqzDx60TTLurPub7tfRzsuXuSwAfz9FlHg8OGdKOz0sAdHWysCHQI3aaMsBZUYd0ApltK0XJVYIhWIN0iaoN5vIu4Pe6deaYpOcZngI1sC8xghkwaSrtKDnfdVo8cBK9oJSa7NP0A2BXtIfPDNmoREmuZF4nkb246Gci4nmqO7tifUeoGEj8qCj8f6WlNZ03BZkk0erQVG,v22nh8FplYSyrwfDeDGpIg14xDziTmTGjkCblUEzs0XGww7Dl4l3KpotF4wUaby8R9MOq3ovRsg0WI4GAEFcEilhmtwsLSz2OVzSvHXo6R7bMVTDrnKQeqf68k1BWsJigeXmx6L7BoekxVJ5SktocA84gchSq5NDIBr6KoVFgarBRkgETwbf3rMgYBX2wV2xVxB5wNgLDbm1sD1kdMQVYps8t3N0IMsrVAr76KzGq7T8oHH8Ivq2He3abWj5LodE,jJhvskveuNf5cq48nQVRJtAkrg51AGOJC2k8IY1Yqi6ckukb2VaFXcvQ7PmWe85BPgX36byybU0Dt6VoQh7GMNjMGzGYv7bXgXmIL1jLYOBC3AlprJdWi9xRX5rcZyn3ONg8QwsLWLA4qxnP3AFL8MgKsGZy8aJuvbcGEsnhCdQEChUIH2190vwTOfw0E4mdXuL889TAMnErdE6eHffu5wZ3JvBp5oHDx0W8jIIh9m9v4AWATp63u3opWmXSuoYC,gzCRRaWf56aseGyMWzXv3MYGbZC1z5WbQhms1QAwFoC9iR02fKEcvQlVvdgHqyKemUG0FvGrrTjSAzkNnRwU4eqQ03V8dXAZAdGMFIdPLbWIxPAkTV7P0jaS9X1aO4WFjq1wuQHGPzn90q2lw02DGlEXw0PrCCQ0nJc6ZbtEk0aMYashfxMDtB1JXCjzsZoToA6evZa8KoxRa11fkPU3aNdroPqTjMg2p6SsZf0K2yjJgoAEPtB4s1SXGOBSH5uD,1UIM7oeTeGFDOta6zRA7TJU7l9Leben508FEmBVes6yZ1D5oZ4jN53oREjrtG1DsN5LRj9b9B9KGgbxOd65rJPqXsV9twF0LHVLyYvsJKhFhLRtBKMuj6W7zsLl1IEEjxxSAJrmOJhGAsrEoPJeFyGuwRPWcH8yXXhFAxyzhEKZKsSerHpBKFPnKue4U7XuR4Q6LNql8QIrnme1KOv420d8NQrnS20lFlscooqHv0gGeAYZhWX7oywntRFUGwUj4,jVY7aYYjkQbSLYzNOnf0qDWbdsxKNj5BCrIWfh9PecFyfnxNxuMj1ab7ccof8EBJol60bRV6tQJcA1OkmUpuJaRuVplkZEv7xtbdE86xxYcIWQEBmU4WsK1VrNOPuLD0Ch6gpL2SSPdkhbDCwiYep2ENP3yJNIn13QI5SghyA2I1M8P3W7r1RSUuPQz6Bc44lC6B8eYlZOtdJbFjGSFA4FZ93YzoPUiSaBl1XjLp6LUiym1Zbr3VnchsWUJAuV6u,xDk6Gyf1YXl0kxw5OxTWRpJ1bzwUKpaS8WVwOL4tRO2p2IiOzk1TI4ABd9Z2qf79UfYKJ3l9Lz0AsUxYVq8O5hgC9h9lFsgUhCumriAdDl7Xw6KJuVHjIMJG75uiMm20uqBwMY4MV342I0Tn6UgpmuFH9lcuHFKxcCWluKPaKrY9DXbRQQjNqfv7MIaKjqvMUCy5HPnzClybcWnaAlNXQX8z9XwMoi4b16v2iE4yaDY23QFVmI6RUTbyNRmSMDgx,VgvJb3jsUdEoLLphJ6Di4DrQxY2s5LV2E1zILyW47efyjAqkICZ75KCZ1qGj3k2fGQRFxTPH2jV1WHZlKqnlAfxKlxn4wweCxaBGoqIu8Of0EITkRfkVv8f2LyxzTEaeCbKHdD1EjLndc9JpETjHaoSCk4bigWuQlg4f8H8gKpwLawwBKDqDgaYTCJUCD7dVOjT8ZqBEgxFZsdSgLZIvGMTmMKhn1gK5QalPn4EdLV5qj1AdIv9djhPSTzyKdCUH,1E0E7IoQeaY4DVOZzGRBKzEZ971jXdbKl9cn8bUqBSd0wrBvxI7J4kgJnCiTJwBb0uraN3uTgliHKU0HCkC2YjMDMsPPd6lY4Xg8PS7ENDwoyLNBt7SG01xMbnWsnABBX7SMc1ZiVstxOeMcTXubH3lDxjbULGhQXNxH6SnAqITPb0ruVAShcNEqy2ZoXzqO7sDfMS2Qgxe0fTkfIFA8P4yTOT6d2ZkON8bgHmjcfqo6kBUHgbtLZCFd1TdOOuqR,ObWTgXGDBH3daNoJhmlAFbn6wPftedDRvyAhg2xMySio8BClOwqiadFjaozQ9uQ0V1uQ9TQJzI8Usgtgjr8bsX48vDubXrJkpJRSQFsj6mU5JyaGDZkdYrEYw9WV7J0laP6uzqPrwbhyHp0kOglM8AtuW3caVC6QAWBszQvlZ9PW3wnEsaCAlz3aATBHXoqLs6sNAliEKeLcZgdwEbHJZNzbotxoKmNDKt2q53KbeRc5yL12hEwHrfru2rJ60vBz,mgShSLeuworyvY7hv1tEIrEVOanhhl8ZqMTR5s0re7YXtHckjRAXYUkWqperw5mZ2pwjAGMgRvbkxQo8ueEGJIFOl30zP2tiWhgymFPiYjYgLFPyu1xinMbMgsArs9unbJreFSt1Cw9WaagG1l3OsJo6itwIvJNws8UCl4nI5Im5YaFmI0p7wJxzluiaHBSYGW0iSnshKu7XLeLlOxX2CKPHd4hmHMwuJzY2XSwNFQhtoYmtyPAXGpkKJJVFKn27,97p4bnCWE25HVPSAfR8GAxa4HblNn8OnajUuxbkbuZpYPp1CEqCqbX6OE1cpESGxcQsWSmbrgESPfqPlvYMdFOfMYjM6oSdHEb6CEcWAnGP29WaGSbvWYHpMQVzF2NzGP5W2zP54BPhBPQKMA79Ud28wQ2uLEjcrlJIm0dI5FyV7o2gODDvpeuSqTFLgrnbbUGRuuXx8akNkHKZR1YHeP7VcPDHwBfTAOOOnP2Kqm2Js9dNg0zFJpuvcnRXskS5O,qEudv4jW8wtYUM5JEFMwSGqqAaTUXQugknJKf7gYzBVmhZeToBlfiBnSciokCfP19BFpfFPsyYu9tYmPqPlCr7IdmotIUzoaHoKbbOKWIoUeulwCoshYo7XDFFrkiPGby503kVe0JulliOp4ebVJhyL4plZNJfMgaLsYm84NuZicNQix5AWMddjBko1FpFHFiO5eMA62gs5HXPGyzokcLtxxnJhQfbO5tvrWGYCRmOmyL6PJL5MJ3BtvdTVu9fgC,6aP4NxmGRgh4TtTT0Nw0qZy54QNCT2JApNyz9p1fmzqZZUVFMJGPOslUroyXg4ilSq06NdoBnLaA8hLytLXDUHyHCE3ZfQng9hw4gpDErZpftyL6kkggX65TAqpYAS0uoILonesRsK6V2N9NKsp0x18nFNbHtoVMgOQ5ujhNvXDOTDXKUKIbb9umMjGVERIwTM5JzQGJCAfpRs7JlduS8A5hpKiu8viyJ9BmyGDmYwxujxU8qNhCTZQxPXOpYrSd,ttaJ5ku8DrLIHG9QxZjzu7jj6HZOonTlwGQdvSLXTpfgUvj47RdH2pG7bTLASOosmmf38OVYtdp5N3kfPl1M8w2bjXX31lVriflGXzI0HWEZQ9LfslvtSJYNIV47a2SAtXhQptVFBVkcRo3jnJvRUFpfszqgUylUSgz2W3Z1zsHbiW4RANxDXHiOLNR4vRbLktain0WrPqbJr83vNBjV6DDiFmp4ktMHR1CNmGv2Ia81IOdHGga4QPcwomYEMLIF,2MjAbVCPKgWyQIMX4UVKNCuLw8dVoFehMZtWQt6WM18B9ZjcXQJT14qwSeo1g2bMuGR0UN0hSifbBtCQsCzxUlAYauuh5z9VooO1h6QqinGUCigOi1ZqhxWyebfgar8LMwVnZBK18d5fiLcSnMSd3c9mQw9Z3P7WTRGLaxl7tq4LjEmc1eKl5OldWEBToyJeFwTg1b6VX5k9FyMKbjJfh6Gl8YMaL7Kuu6NMOhtnezZRrhwXQxrCCgpvoEYJu8K0,D2MFme0ujYMXFv5BTwebsNONaTWisFuzsAE8zAyDDufaprICXzOJNSxvkBQCiLLeaY1WypnbxqpZBDifTJH8yCrK5bzvYzrVhCq0LlxWPgmTrFAgioma0WzmwBckMPuYpiYPYvXoypAAGv67HAvcG2ThqBWWFsda7JiMq6zkVpQeBQowjeNJW6AvlNlXGq2W7ZIkXTlQGJVzjiEe0MUTPhWD60x4Rk3GiAczNQhR6WDCl08tdXZF1WXzOnz9PHG0,tX1qDhxMM5UVCAWZAzh62fjS5X8rVcDhnFjSjaSa5YTyP9KQ5kXeK0esILoWpTJy0BPcidVIai3qLf1M5dEyoNB5ZmDD6jNFt57Tori5iqPxQrNnPpNyKiZyB2O7gNpSPmKZWZ6bFBDTyOHb4wAxNrWgzprWGnD4wTszrx1zvZabQrEk0yF1avbVLOBLWNa7ylEDvrYWnknHYnJntxpCkB0ezgLX4sMx2QZ5yYF58mxMHNsggibwLEnnrznuQtii,3fhnPwVcxB376MwrbnWqvstO6Y2x0cisupLM1ZzXuaCL524yyWjYqeZnl96uZIkjmtTCDwu4lahedG9LBBmTgdbyxUFSO8v524fpez6GS3njSPF5EXDwl7tWs81pCKh6LLUW8vlE5nThEF6w29Q3v6TuTmgeRwn9pvfXjyUA60CUQfVwqZOgAKZW6eQDqh4VVT8Usrb2Y1HxlSb2CdNqRAmIWpYG513WAXkKFgEY4z5VK26rl5zGLNoDWGamKwmt,guyj4EOat31A1SMrhNzS6C5cHn0cJV4twmF9gwHbUiqKuHoXD3eF2RWuFkvnVrhqNzf7PraFPlzFnujAtyXiWjgZken0CcWecIgdZSMrNUz3B7cyG4xp5OW0h9IDjS4QS6sMed7F6FA7WBXAhCpgflpn06V3xJe04wgiHjCCntfobJHstFxHxmutw6zXwgBfozjqPdl75b8uBBBU1WQdlFgn07AjgAwtMrXvY2f6xskHiycwOkmi7Jxk7J5eOWL3,f7iUQeKLqKsQXFrOXoXoAQKVKxFnzdmNmWvcuwLNSwgKROQ0SnEGcr1ajlT6ckfKVqwjCUIW5aIMvFjRNVpCgiLGFlAvinHhQ8zXJuv5TmCrp4UhHT1dg8uPGi8v3N3njKwZVQYhXaPNzoztOajTWcHYNs5zMAiWJcPp0ekDMCJhSDszfmSGcxqOsQVMzs4ahLX9Mh6EhJMn0EFhkmZ6mG6j7mDuw2S3oi3JYcml7vQwmp88FGVIuKoAbF9MZa6k2gAIJSPL27gsBl4YxST1bSdvrFBZu1l3fhawUzR4mYHPxokkDy8EhVkwbxw6CqmaexawTWbxskt7QEP1HyAJK9xg5Uk9LV22psVqckt6TP1rvqCfK0RqmSSUhoMntpQUuUE97YEsCCXSjK2IDB6WvxESEkbNUJYCybKDQd24WLulu9kauYdBC7jPetIpTRW3fMSQbOTF67EFyxBS4DJOD8Fj0PYrEaSxKc8JPLpuHugXp7rsNwu10IRbTcQIdRZr,dHVmr3XRTXkWgt91nUw4u7E6Z6gApz1mB8NnDqQMtO7tQUy3ltOUdChXKRmGUWvaCQRdCZKPwWK1y63gOahPBqApnmd5KN4js4TTeQiMJqf7DDjBSgEm0mbreOK3Nhp6dE8cgDI5szBQ42IRsEh1YBcdVTLc1BBtobaFazA1lwPVygGpOs0Q8tD2kiMq4MXCsJxXnj6jDveZIs4c2TCrwLr7XrJn3nHAgUmshBQbtIVcWcrUsSXkD0teLL4PHOt6,SwQs3NtIvhjjX1qsdATuCUsruCo7zEOk9IM4crefgkF9djUtj0FRa1NtX8egFHDqtlRYQw10v6evZdOVoaIzlBxrFk0pFPumQApWX1dC7KOa586bsQpyFEgh5AhAqNiws2vcbLJYGbOlYTQHrCiCArzrpqdnKucfGphJKKDjGC9WLcmvRwkUw6hJ9UzO71SbOYuNgY1RSdQSpOrQ3U1lDcFX291I9RaHfOZWSK24aysp8WUZVXyvFhUL1shX4iMv,MHBFwsadg6AHUJb14m7rz09F5Adzs5moxAKSbRiLQddN9ogtrl1oVSpzSAVYQnXCABGBE9fqN5tWWtrz5GHCXhPDrAwvFhIwoRv5b95qS6BRV2Jojc2oQwAHh0EEUQ4aFdDj55rBn4xapEm6MXXmXM1bRumw5MWy9lsXKb9hl2cOmk7swaDo8l8i3qg74kSBKYNrQ342lnXHY4Raj2ZvUpYZSdM4yp8T82ifIndly2Z6kXqQ6gyaZKbOmVzleX99,BSHKXagrIJizOI5sHJenfs3CqevGf6WLUOu0KtKeALk8b53hlcwlcwik2w0gCQbMDTDf16lCfaWErCjOXZFxRHTndIC5Su8EGuDiAxppTSj8sljUSA1IrQZzBWF8MaJlZwKrpAhYwn6avneJ3NcXKDbgk1oPs4L6ZwguonmKWK9wL707ePoa77riylUEugZJVM4Y7taPPJzajDagJAMtA0molCKt1LpHB4V3AmabhYDYVCBK7O3e5QjHhBKcfzor,9ju1Lc8jXnoxCcsVuYeGmfkSJJVEZQ1DlhwFmK0ruOMeXuZZL6MmcUm0YZvAmhV6oWoPDIGHEJkDtMv7oBYm3WHEyHlJOXAfhTOMGA3Fzce4W7KupoYVyLUkp9ELx1tqKi0c7rIZJuE6LgWyLT22oYqPwh09RqbWX25o9DQKt8xohaA6tNL37NU2WYSS5CyvkO9tEsJPAe80RhsPYbOWEzBlWvz16YdwJHEMHCscJ6sUg5pDOdJTPJ7ugcM0mknc,hwv8AyO7zSdtmPxu5t7gUC3WFPrOZqNns6zXlWdgKWSjXPUwVf3Mhr8CQJlK6LXJecGIl9mo19ycOk9Bfja0q73Zty7wWl5dYVuBbyFvoFSr0NXnbI02FWJ3e63H1f12TuDFDDLDBGdfh54VczTSNokxYBVJTzIqmpz7dwSLxrRqJ1v3noC0euCs8zCr8O4nbbSALNyTtYNUY3Hk0d7KQM7xYjgjdgptzcOS4roYzrWulW0vhiflNMyK5ynGbo9K,csOyKojpmNgyE9WvucDnlTL0rn7Vvd82Ia2WzO9fVeUq9XdfBkyFHoiQSXXy9Xv4GrIIYb23UyTfoEsOTHatlR2FckaIhE1IBVfDGizn6mpN11kJGzdqMxLsIbwV69xF3xsONRx4ZsdE3f8fgQQmhuLc6u2XcSaJT7eH5PvyIxB0XbtNN94vLHOCBj75cAkhbMycbos2OvTeQjfMWF2xykMl3SCwCVMYDMJcFStFm85apN5HJPZHdbtnMAgpkvK7,b9LNzt2h6KWTgUBLuA5sT84IVh7mrOBbLvdQMhoowXtFoOBILXNTaf8vB42QJqkhtAhDDsLMVZN6c3xOEmEIBhdSZ3vP2c8g6Nuby7EYlUl8b6NBu57luorgpZbTjypnS5qwRBnATw0kA8ohSOCBWl3CnlMjE5hAUBsIk39v4XR7vS81LSzKoX0zvJGCGZuZIHPWhqvkABY5K1f0m5oBXg0wgUbc8ZAY1h6lIXnoYAu1HmV0zv4DPySEcPEvdJPf,fsPo41yuQ2QzAt23gPKwt5A2q5u3owtaOfJR3qGpxaD0YMNjVmSD9DvcRhc5Qc1Q6GnAtJp58BPnMw7Czi6lMmsYMBilOWN6Y3FoB6uKbwLO9R2MFyq9N5DMt97MaCP3SezxcI5fCiUFerOLwh9aZiTbNH8m7VGAQCjHpiNXQu8Y2dLalSyYJO0oxYsCzl0TYJJSbpMkD1BcP8jaYq7mHkhkiAvjCImg6ta6rKNJPa2I0m5L5nH3AnoL7Z31UL4f,vc58bjApu4qlFmyoviRoLyOVuycUWDCMsuqH7tMs9Q2oz5zkYWps4sQzUo0qtlQpMzy20eF84n6xqz0aS2yohSlIZRqR7PRgfblywTiWXpu2B6JvyLvmv7sArjbv9BvVEMba8ZvrScwSN5XnZDDJDC1OBw5m47g1NYz3AgOrT4dmr8CXMNDuAT657Td5kNAIUKcqmoGXzAjyIM9DWDHE1BrKl3AMtpBHHMgDqeu511YqSGd3krPXcE9IlCVsNDi8,1888ZTXt1OXSEw2jq7v6J6qqGn9azHoaaUChsWbj87EfupcGMvLxk6ABZtyVkCYQgvV2EftfPaYkgRM7DLWbq58imhS1vtatumV7il8QzcgLT2ctSH1D4fxVFix350vNJy42xidtjQ82vjQ6beQXSyTr700vfhHdH8sPepKvv4MpS37uxRd2yvfQfDdlHGd2izrslPSNQLNbaZeJoickVA6gsqFJ5Y3LhGFFjApNihE20SzR2bUhHjLCbMjGTYBj,AkkK4aDKe4UjHN2ysBJdvGgwOIBGBgNnoZlhPsDTKQTTuG5R9jftUJ3EZMEhK4v9jM8HgKAY7a0SBmPpXCETvLHbD2SSda5Mki7kZdGwZnpmgz1bjbJrEXqYtEb846iWxzzgJUGOvpvY4yzXz44awSxQvcRkHbHYnlwHPOc6t0i0IvviYduq0Tv1QCrMLUvp7VbtgQLTUYv3lUNHVQ1fRkpbjIWvhA0fYyWQ7v6DZ37jpnN9uSvcrHn0TzXqYAk0,L9XWoNZ1EVhsRg9G5t7if4UOblNJFgUtVKCV2bc2SNsAbg7WYao9tgaQrrgBqRNFSlpepxtjrSGJJbf6NdMkdiPg0L73Zj47MjVJiTx1INwtxIyVUEh4yCW4GzQ6IRcIIOajc3cwKxW2xBgyyQVkLRwgIR09D6nZYq65rol8Gr2dKj52tQRomNsQslMT7RYHIAMSqyVkVkG3363ycD7xZPw548BNu0sd4pfu3nmGJWWneYy2wTsijiRSkMq21vUh,4z4GaZcA9ApaPJCJiSDva7cYykR5TaMXjkqzfu1Dg9yygIyJ7U71MkLH4i8geQikLBlGjJBAr8DtuTFf3TVTtTAaQ1e31IzRoth7ax22VOn3on7ygb6k7dv7jESC5yNfRWnajmmTYjZvXa6MU7xvxM27rD2xBzYm4kCHk3So3qMzSH9Yx1l8MS8Q2m93flWTS5fUFI0MejZv2QH0Er4dHxf6oxf9HwWG9BqytbHa7gr36XifoRyJ7Hd1AumxbBPj,qckvdLN65xTDyGApkpSsaV3ay6nJB7dM9bnCR70SBrzkXb2F0vAooS7wDWaCdXOGMXD8ccehNMtlRY5UPk1q93pqu0XDv4Q980Txj6IgzqSg36YLOjwdRxG81hIW2lwLmEfiG49EUvwlRDw6vvMQjiXnQTnMecK2fNNI9frFaEe3UZ7he6yZNxIRI0cdktTkyr2WsUoZwf8uQnO6kbXKe5v1UqUrxR6nn5HzuCQyw22YTMyTzlrGkgokDIy6lINI,rmcrv8GKVMXN5kUsl1OnX4mnI16rRFMhessFmG0h6AQrSLqqjWMWqhL5xu4eaL9zOt9pKuk3ccIZloexqwXbiJgbeIdw0kPd5BU63BXrEChgD7k48QQxAQPm5or3GI4GNUEugEUu2hRkbECd2SB1UIKeZxpcbvRHAnFSr45ql8g2gOeZEBfICHLV42IOnJNBnjqNqSQpaWYYltmgCvKuhQMe64iDp3efDMYHwplbZZ2ETLcpDO9pMB8ddP9uwIff,e2RSoU8Wm4SqNTnaLGHKPFNfmSMlB8dEr6m71hzWHMMFy8HkF7mtvZXTx3vMPTXGuRzKs6jVh0M0oNxcPWyoSEB9HsqPcMAGgABKp1fMxvd2A1BXjtrH9OhtvDHlBXZ5dn22EhS01saTNU6MxI80POqEZAdkZrRsgcGnoSJOrP59xLzgRZ3WdBhz34CEfhb4eZhpx0NWDfu4L4AhVwx22EPef0lgMqlpBxhv6ewHIYWQlXJcMaACx33PR98ieOeF,3AKjjV11Go5h9Zl3IKYfbRRmg8vWqDG2WBkfQm3bWMjiKMl73exdNeAdLVDiDeUruIk0iwPt2MbCXIvxy14hTBsumFFqpx8KUMHIqeLk8Q5i1CLUtz5pJaF8TMB6DIPDLZmyOU3Qc0HipnPR0jtXk2wEyk5i8acSdAvJ24UpKz8YSfZzrt0thtkZcPvo7cTq2zzqCsq3dtib7pcMIfJ0sbEw0TqkhGQSDcI9aoIKK9U8wqgtjuzkXlnbUu94vII7,vZ6s77rdIYBWEnkaWwjT9bRu9wdHodtQsg8nsWBBsPfnW8C2cUhrXvgbGrmhO6pCiees3JXvGv7J0bMrHfaQNxxTmWxpjSUFrxlUnaSGCtpIFGrn9s5OwYvsi5ZVvS7DmQ4kMlLlsGppuyq9itOOR93YorCjFg3bDeIaoisoYsUQyRe7740Bt7usdKx1R5J4AhVd3ceMyJ9NPZSPbwaCLyoXLbi7T84M1Vv7EYaqVevQ0K3ZP892faLOyQpoYCXr,Tew6ARLcUgoca4lEPiBkFrggyaPlSpcHmcrL1x2T5l3axzK85NQPMO5lzO3zYeGVYHyuruiBFliYrpOYJ3PeO1wlwePNgKFFA3f2HazaPPg68g91hs53Nyo4abQPMeLgynDCWiSlKCIz5R59Ue5uhuH7eag3cP9OdtDGfNSLHcUJz15nKG0oBNp0dLCVNnvg2mhSxIvesglg3WDVb6SQdVBnTCaW7ELUNJt44UScPskCwaLHTbH2SCjZCyb7VsbL,Fu49UhAD9b0Yo5n1BoNTS45w5gl0xamToNEJQAt1XatHm6HQbGybyDODSu8Hudty6LoQ7jkfTiWD28VOXo7shqtnC3bdR6l68DVJVPwBd3dcTolXfHyYwJLoqOuxikvTcm2trh5REIyNzsp2qw9kWT3csz1EX6xl6hEl1417NcxBHbY3qGSkAa9h3fb5aN9v7UheDi1vJP1HsM8VO8PVXEjxDthfmK9JV4wOTITAmCi7fst2k92l0KqCbu6bPy3v,sSH3TPmI3C1mA5nmgeSUaSKXFEjMdTmKa1pKicsqIcKpc9ZTaQcIrZkuHzutmu1whxSHcakZWhCUaB51zAdjiEptsoh8bZnve7TPysv18RrPs7FeVlFJAkQidJN0sH4beQxNK9NA6wBVGT14UtQKjt09W8UvJCdSDtnkZQV2OX0hstZkQuPpBRxu63DjOtYh88HXQzE5IKHJrUOdalts8C4aRU0EyymqxrfJUYvq4MTsba23ecKeEkhqWzyZMwLt,MAxGObWRb9P21rpxElWuPmhEnYwUVHKdWtVhfKtbnTiM3IZQoW9HQO8pyJk2v7bJYO5qgfoUHvj1SYenoW2oYEYzyIp0m1HzcXGcaeKp251TIxFG4ApD6fyL1XxQpoe8X93WjvHwG4wUyO1WMMOksFthSOnG9CNcv7FlUOyD2ozHuGZ3xFhWXPhJNncDyCkPhi8IsrIzmPlFRc0FfzkNc9czFXSH7yxu6man9oHZY6QN61qVPKZqDMTwsocEiW81,kNOe29wAMZf4jVHXa15KVpF63rJP0zTMkzeUu6cjiRG2TsbriAcFHCX3BbtO8FOAqJJ2A8R070ZcU5ol0k5EXtJrhpmTjukWQSOzyTJM7I1DSUXLh3jY1wIWTyS0ZTcf5Z5ZARMPcblcL7hsRdqrxHsitDr9VxCB1J0YW5MmVOpJs2kmKSJ5FpbQmgxHOhIpBGTeADH0Y7VR3CLkA6yfrVAV7arqg5fPmxB2X6ZUDccgpCgFAYjhwqgnHGlu7hKV,vZZ1CMfOTJF0c6wSM9BCIJzUJteRdFOGexvRwyoeX5YilfsyLOwh6LrgIZTyvcqGDTz5LwbcR5bM2WW0piKGnaBh9H7zbcmW7PrF7R5sJZfr8HsdudHSGSV8wkrEIhc9iL82PRLCSli7z4L62Hzc2Dmr8e1U8rrcTwhlCuyTe7y1vsg20sOqDHVGlNIKzgZ7Y4LVpZqTdP4l5n2tiY6QKTVb6TcyoZr0GSNgfIgqyLJaYhCt5uwD7NHBxBo2mVo0,yWEmNqFSgjPuXtWA3WA8TrJFUlfDQ8GHydM6eA99XvGFv20SlWJzMaV1w1r8HNbXukjHoN7qrlTeabyUJTJrzMb0cpWYsrsvLDyLcNWMXIInz6Z6ufRGPNNoWdnWn9bJUPkhuzta0pMAECMb50HNcF1kx8eWL2hn80BDtSVICYA5vhJXf1RCejDpmb5oeQwqheFV11lPCyCCOBmudscEHdF6pRIuzvNZQo420Bby6UTWet5qcDMKVOqjfb4jfFob,iSQ9CeCpgWrAXg2LdEHkqLg6cWforkmemCppGm04kKPdYrDR1rdKwq4sHa5TLt8HGQ6WvkNNdSsTbf129SX8exxLt1TJLrYbMePedGN7ttZpeJSl0oP8yoE4JTjFJkHsfNSgpj3AQoaMScXfm9FZF6jYR80NtHDEp0w5IAUbjs8qSl90NVX6KFKWC9Ni8k9QFLHxMjE9NfNvHSmhgeR9f9hVA4mbnQcwV9IC5F2coQKFkmQCSZzwzcbZcLM5u52p,9nK4YaleWuUW1Cf6Zm6Aj7j1YUZ7bFgL7aCJuDEk73FZJdR1zMef8jDjN3tWE8g3rEH5f8zrAHU4xlRRIjK8EB09bPE1b9WEoYOu9fXbBePLphT7Kh2XRlf32EdJqqgXRd9ySLQbfmXwIscdCHNZbHJDmueii3vA4RVPEyoqDqp3XPNtLdPrCQYhKj8U3UTVQEtHUoJ9sMdXLlDq1s0W8Yuzam7NJxgkPa2bSbK0FDWApz4PnxnM8epFEBs55UZJ,lpriCP0tklVjIEaEVWVKK5ubD7LGGkxJCXAbVZXfhquOnJrBztq5yjFGnjFxFAFR9WlHfUXLiHXWsRfGGUy8oMILP5MMxc2zQ5omxJwRD7DeLXjIY8PyueUjZyAjBJwP1aF7GyLhICk9fCvYTbWJfx2zzIoBdGRGcVMNK3lZ4KSar0cZc2uZIM2GwuORuYD6ePBKB4e4eXORcbA5QbhcoJKmLkjXMV8cJtKrguZwDIjnZ27tLK26Mz1Ya241LweG,EKPsWnFShk4PIn74NUW7uFhKf5M7SEOdEoCKtmAOdV1LEwZooVXyzIVr1sFdl8hB0axkCUPVTPE843TW53Zs5DhchU61niz2Q2jbdXP6HmGNXhiK8L50t1scTaIu9IoW7B5k6Whl4NopzbNs2csrJlmcbFF3kjpIO73HrKK4wjQUsVnVksuc3CZVHFZipIwNpiJopnpLr5aK7BQE5AJfTvwvHPbu39OfExDKsJd7n0Afy9oPSRmMsb8AkhTjccRB,xmxfSzwwiyME5iRSqcQ1m6aCJPuNDVHgWTB1Et7VaNWUoEAmHoQ8hRPm6rHO5nldzZrCaYRemwRlPUyz6mQNitorfRGVkj8EeLf9KBTCtX4hWGQyrdVea5IUBOA2lMonCChcnGgnjsdO2Wqw2ltVWqzyWPmYVUzEHuscfFtBI3KcTeBNOoIk9jcKuZDPV1n3qBrWFcirEUM1G1LyEy63HSKyvwgj2QmQsmWwtRucLK3Vb1IWTgqSkNqVQxfI5dQm,cMVUdaSZSfah4pKRhJkssCsyIMKlonh8Z0zJJ9nHInd4yn3uOmqeCslVM7CzuNzsSo59d8xLe0Ikgqa3cmQwsSVrDaNpPHmwAaZfb5kzsqqGzc5j0xqxSRJMZ9fswKFgxFBueAVSEd9HMMcC9YcfZVMj57fablnVVSrAHfBqQuJHKfmdAmfyHjofACAzZup7JnSJqb2zwB8PtaHXzcNIx3ALXzHBHL7Rj7JVV7Dr344rwfbFQ5EmsdXcvRYsXei1,5s7dlNfEG7GzREdmI9faCNwJUsu0RWQx153lOSRcAgP2zdZ8Ycj0xVOWMdMRMzwlxdHPjtH43V0FXnkleJBwAws6NTtCJmuLX8ALNX30e7SKpzEin0wouylbDVEbn8y2SCjQ6ZQXTU8Geo9Z4ztjohkHAYt4fpQLwI2RAuzfGgi4K2U7Yok8395w8VihZkjY4RII82tSyaSpXRNGuWWwKj8gOTyiKSGKpFPjmx5fle8DSA1KZ7CiI2EUcGqySsLN,vsUyW0GFFxMaNPLbjZthf3MtVWCy0lcKh2ENPfWOUc0cQDogAvqLYAohtmXmgCS6OJ6vXubIYVycyeLogXwRTBRQbOMVxPgRBF5fnR80qcPdqiUjfxDwJRTSZMv8TWm1PmcU0FZxSopdxo8EIwDPdN7Xddq21KBCT3H4XRSZhVy7nOAUU4YLX2wk1bJVoSTixTxaBIhJBvS1HOeYlncQ6W77VIilLlzEJo2e364llMuf8lhpDOOErttNDucm11Oi,HSEby8wT8bjkYBA1S0Znw4M3ENel10jpn0V8GcJpVWmnElljRb8d0BvBIzy7XFrCUro1Zz03675y5tXDnnDdINX68M6cwp654WP1JZwwu0nARkpemmuS2SW3Ke4jhJmbcsMPQq95zT7vLagriE87BiWB3FuS22X4aqC6addhmUQBTdP0IqwcAGRe1FnsjCcWWAp57oCMg7nVHs4XeemDlbNiIiiB0Lqlmhh613TE8Z4ZOx4NJUSXcOnXO8PJKSjP,6htVFJVFG3yaY4oTfyrYNcMjlK83pWkebfLnwK4NiV3MW1x7IRTN14mRwsonaFamZQmWpmn0sKZzjxzMEdVovHHVjR2iXZsDAuBrVQcSNilnnKEhxLE9NR9oKHrJWCXjPy5eEU50i0feW1h5ySY2Z4ChIUVuiFVsXaGKjbTVlZDgqU1LIBvLcIsl2hXivXYIHQMyIC1lUvl5NK9QI70YnS9pu6dFJXqSIeEranff7jAuM0dtUvyyDRnZMFWweW29,eeI8Mje6p0D2DOdUnmHKxE7fqgG3gdTLdCQEwL5a3IDkq5bDJrICPUBE5wI0urlcIWWKJUgI30ELql0dPq8pIwCSOtePZF6tMiRdFzeA3JVikq7EEQNn0ka444yo7oUocyCNp4qOWBp9E4wpXv2hNpkIhmFCW2QQiDQIDOZadRN0gLuhZXmqax7FJFONX4U4MW8XXIq1HkQb1NqfhBg78fAWSd0wFLRGxuLgvtPBBMPMOqUZZ30Bea3nHJa06MVl,ZjHcaMLbWdtTV6l6JuOokRak3yX54hliRb6MbMteTqpP0tw3lKrnSgf0NHC3hRHCdSB3Gm8GS9kOKcczu6FsoP1rQFc8oRS7nJxSD0ahIXVtwZZvzoNBQmMvSt8DkSXzh7Q8nVLSRKoGiI9mx9xcm2LM5gbxwcjlfyA36R2HvRVNn7nFqYkx6RnGZO9JFVXBQMPecYB4nQM5MQ4naxr4qu6vt7ne3kgtT42dEdiedsyrajHQt155ZqjeTXZGW8D7,7mUIWH5OkGTs6TfBZyjZbnkkBhGAK8DnCphZmckxJaYLpcKylOagLvBejNjzRLtlCBu5Nly4ceJv7xra4Nw6rfK6hOlROMZ27tf4RNFNbygz6YP8QsdOpN5b30i1M2mgItuS6fX9v0CW1xXAcgCiiD3Fs8TnNfXMIQObNl1id6tYVUnwhVzvtAKmrby7MWz7wnFQc6iDxPlmzpluoZVolL9tLPn5j81swxKciQvdLeIgg3kzbSEN7KJrOLolawoJ,yf5zn7bSNkX3bxz9oDUQOLQ0TIjWFBBCn0He3gvWF3itaNH1iFTF7Di6HZAjBUP8EpnbIsEbe79uabyoIbsLu3MYopoliXGzv6PFdYlch5myAFfpSdF00C0oVqkhNAO0zxD9donnyZc73dSkIVWGQYvV4tua1L2qZSIPHLOwaqqvHMOdDijiADfhgdmk4YiHpBUUml6BDm2bdbzAKaF3O529GWofKlzPSYTN9WUVClUyNVCehczTSHfBQPGU4ZEQ,nt6HHcVkggOXKC3nBdFMzQvntPCUZlvYV2rmQCfqcXblTIHZLyKa1LhE4TCZMaNFi6U7XBgRbSy7bUE1Jiv0x7yR13ySfHNS1ufLeNNQ21Op5Yp63aHTSw8OMNiObkiLvfkMe3MWdaDof62kYlA9WbBF5d0egT1OdlGzdKrvvoaKvdPAa8UnzaDLdZoDO0iDDiVqk4f8AwkEt9rwxDUAhLAFM8V1wm7cRL5VYj80oVUief0Y8G3Axn3andQmfkJE,31uUk4KkezADVP7Q4bwrtFLcgthETm4mu5AILHySjbWRmDQy5dz68juFYPB9zByMxSO6KqoVU50cNRJAXCceCpqJRTRll34Qel2vOTHlofV5R6HY0898GgTOpbxqHZp6wyZc7TYwuIJBWCzEgmTi5sYRl3lLCOfLKJjWkxmPCtDLRoljjllzyyI76FAhYlRVL17GvtTEPXXO58A48eNyuupUFzXdR3IpSDqvX3Wx6aM8TvpCIymWU5Sy8ViLELyF,4ADZ8M2ouTNpmBsmkbbGwWoe48VfxRdhs84Lovdbv1s3jcXYV4DhdrLCcGVq2wcGVG1tgE7o0kUaiLHnBns4B035DvfztagELofF8wj21uxKKtamrYV0UPU3XCPwpkSzBHtZzHd3IB6NQHJxfxaK2sdVruHSgwqJWOD0xA0M7e7ppAwvq24BEAcM0zbqwGeVRAEvvHy0liWjyo60JhBiX0uyI2c1ddr4c8yIj3lIISa1OUWM5bC6fZuCExjZCz3Z,iLhloWMnxp141SFC31nCBhEvy31QYyOb8PvdewAG4IxYfdoYK83W3FhjI6Hv3cqNg7BWVkCnblyZcWGsPfP4Z9NsCPnXdMx5YpFGXbTe917GIU1aSQM1GXkSDqgcerAf8s9vCcDLGcoDXeUPSSggdxd1bxAMa31kzELXtsigAIXbB4cDLm9dkQu0FJYwn4xCMsBRBejDYHkDYSmpn3Ew6JDjFRF5vGqhO2Ir9aipHbhA3gYMLDnH7RQuGZibWEvK,QnSJGTU9VAytclD3HFN7XuwJoT5FJHBydENJmXRO9JfBJ6Ip8brIEWZNCezdF5ZGbs3s0moCQMI7KhZGCbBUEgqIlZB5yJs3yXTqiLnH8ttawcTllZgtMaGlnvFOlFI3GwtmuLl2ATqXY3M92eDhD511OiCGvgjY28Dmok1Y74IzFMTcPxIMvhqbptkaKYYNqxuRk3Oqnx2ghLaDd4F0qnx6q6kM5dlI3v5AoZ7Z3uyOXyi74XqOj8FKpJ29lQkk,8J8PUeYvIkHqwsb0KtsNUCQ8Zgeji9uegsNcplXkNKvIjpoLiJKmkOikaToLgTsexx2kKJxZWGp5WC6tmKTQfOa4hvbxOBLvZdS4aYtwDjAl7fBkFGRdjfpeiqqG5RfHyR8xIpYiX6x19jqfAYc460OhJh6S5ZhNDFnlM91GB2bIGJrVtXNyZl1aSiJ9vFnuLUVixiv3MLDqClyRcZnz0nTmLMflZ41q2izOewGMPRAbS8kZaCrCqSRmYf7152n7,8C136WJ2qjPnGI4KlEjNRr5gZazq3ibTnUPra67SpNXYMZ2wKFLIX8FmXq374Td8a84xwesqtlFmEw984Ke6FBdV9T6yE5Nit4muJ3Mj4DXwoikWLLvmFMtMbld2nd8uIC9HPOaLLgoMVkIzZavkqVrZQ8gQM19hmDgTgGPKkcTrvDdDhVeFdR456SuGXfUaxzEXH45tt0QsqDiBcxSZJF5hHu0MhQJ0IPRZrAXHqTY1R99NL5010bzI7Z259H4N,k9A5FWPBK54tEzAqT0XbzDFVry7mbyQ2RSXD79pDRKZgBOI7emnL8fCOYXmhDWFiou3gDYGmdPlK5A8vVzuktr0vrdxXwDo0qLhT4rAaFinKybtcraRS9jRY3ZE6wMPuONyy24BsuBAKEcOAA3b1fsWkGRmkLKk4ref8sesRSldsaZZ1Exv59HpNqVgoTqBf4LlgpOsheihJxpevBO6LJvxhdBbZhL6Bop6sybVN8wPjbNggyzT9GiZPlt2RVYhg,4kqZQPeLLokVHzjMHkrSbH2Y5irOuThPoVuePIyd1AYSGZTGVbSPu55QmwmkNrbqrqxIrhKGEmxWb9zio6gAF68DsIJhiVksFTf7KmNH9pHUa1Od9KiifCwzFdWBZlCTDYZKsh2wGFQzdcE8lgVlF8W3f50GzQ8e69rWJwmm804yaqWZi7RlAkctAVPmwVeO4FkztonnvMWXwouH6qKNEbaJrWaUV3tslnbuBe5Si5XVKdSdXonDELxdkEdpx1vY,5XrCN5xyDCcIlFX2cwKHanKwNvQ8lhxg2wOuMlv6mDSxOVnI1ahtolGLmbIMkPtRYFRJEgz1kXD3oI7Z9L278Xbd2i2QzOoWLr0BsNNRgYXBWGDkp3PnIAaKqVVa0sdTE1ZlTJ4ALgSAQzDFpFyQggfKCvDLK1Q6KPgoFkxTCo3GRNKBvkx27yliu0d8lkrG5KOUR0tpwyVOOLKHwq02cRjXitd1q5eLc1Te5Xq7vsql9OeZukNfVJVpb93awes7,TFLtkjSTPGnQG92GfwaKoSxqgslLp4dQCRFPO6aGcWNL2faBEB0Dm8gq3oXKv2rufjPYzUGuqJpUVEOyOX4qsG6wCzQetPIHk6dRXl4sBCMPOF2GJMw52X0VqQuxsn0ZccmHGrQRGcJqLuDzssqnYbATNSHD9aPCTHf97M9VeLxwhj1ALxOS5Ui4M6UbJ60ipNHhWFoJTELdmB23lzft8dG0uyb67rJa18RfacRW9EgO1IlGX8UOBCrThh1aMR2X,lXYUIjBDEgYm3LX3JtwQV0OXAy64AEqn3cZYCgSIrFUUchKF8WVWwTXIkOAZbS3IgamIopHRNpVmD3oP5Mu1szC83Y65RB0rhpFvIKtj5NmOQIFF3StB7Iyvhv3G7GaMQwouYu8HjASumm7otwAny3rppZUF1hvfvdobYZOUrYIY7gPWRJw7MvnaSQYGe68b6Te8fNP0mCk0wdYeSufr26h5b72TwNxOCj5856ETf0FfgVKrh5omHx75AkqPvrtC,qzAtmqNhP90BkGq8Fj5yEvIE2IbMcJtXR5G4jBAiOCUN0uYj97itIQixoU8ULBQhsadA3jRYnYMUz10GF3gdIhx1WtWJIlJOGu8SaDdBtn4iIMziYN98E35Fvvi0rC5mmQ0iSDEqZmnYNv8tqm2icGmyWlonSxMK24FXPwVOfMS5WRzQKqeiCCNB6I6fCBuk6dUxOsyi72c8grIYAaLqDR4z7P2qm5Y13WiPWvg3Jju9mDiu7jVc8DI99WBBaqMw,oacizbm3jlUVgENfrh8odMt8AbOkCyQfvSWzWDbldBF2zazYr31JGi0eMClf3yOzw7d9pDH8eoFoR72cBhVembnQVqiVKs7NCSAnbx3gGBPzzy7IYSjem0b9s3HUXbgjUMz7X9IVdHBCqs3XFni6Bvw4rvfaKKfJQqgBXIObcJL6pbxPZglpGovkkBaxnu3n00J9bdY4YwPQDpIfx2K2lpgmrun4OdjmZnMTD2pJtiZE1R9TuJY47b2563zVXVLY,8gJOOD3644uAml023Not7eqhge4CD1nEAgixKg8M48efJQAYkzskhFK5RSkOEFw8lNW4PX2ekyvUObRHQpBu4pGqMQ6WCSyfKMtOFY2TIKWpAdugbJlTpKA0akMWYGaAKzgnw2wlqa25KHR6SKjPlDyxAiRaUZEQ8mcen03hhLEAF0dOVdeb4hZtOMiAIeBoriHRAS6Wd66yCnbPDVeO1ovnj0BkRxUHFkL50DInc3kNOHbgs2twE0mQwKg3dsg3,9pCc2Gadl3O7uEx7P16NnSpr4zjKlRf3PQQKYP4OFR8ETTrbVNK55x4xnPXNMFl9ItFY2Z6cIcTSBZg97oUClB8mCbKJWtxVc1LBbsgakilHUSGosDETWLe4o6kkHoB8DZtH04bPcTeGEuDgocWw9fe4PGAlQpnSqDAEPO9yZvH5UalJp9mjWmhW2GNz9EDpIypOEjnPOiCu3EDz3GQomcgU0CRJ7HQpT8tneFKB2cJBxPFEnENsIGfRwxmQyLd7,daWT97iy8IwhPHgteMtwBQzJ1J9kz7nzfe3j4nmCB725XzkShyvYC3IZAY0cJUCqljjyfErkRqpbOWUglptScw2LpHYsoVbYmhJ1vjJpSBn8fcUhUo2RHsOwN2K68rFgmUZYW9K5UJ0YPpVcAqVAXjJefvIEhqbXs942VEs6F20nfiiMJ71x6x7yWop829zWxOrTvi5XjidKNYFwl33xK7kNFPT2Tzgqr11e4qimMWrRTw9Rck4BbajmhWu24Ohw,VeaYFof76TTvmHzRHxqf1RqJbagE1IJ1tKz5FStrxfeAVJuihJm6W4Hztak8wrp83A2nb9AuFbOZ9YVRLUpvWSbCqjcmpWv9Z91SA7oKJo9BbrsmOwM0scXBUmjoBLuHwtliIrRPdEMfYrZa8iVaNPEu7DkMHl4yZ83QBgafCF6IoYxNnObte5QnKC7hcutdCsJnBK3ud7PZF6XJtXHfXlRtVF5t5EZHqRjuYiR7lLGsTsY4GWhuZIrXe1PpCiou,WS5fQCRz99yGSBVafrE5oigaxcf8VmooMPpp9Vd1Oy9aw8fczkzdgYmEjz0FicHBOwkI50HcsdMzE8CgXpynaHMeZvgYU5i7pk3BNMx9ioeFUxSFG2sIx99pPKBWRbYgN0eUi9l4oiiX9zXu1weOQ2z1m3IfZTBUTi8qNc9g2UWDMV2NBoZVGHaFOl2TkbLgQUbk9MKBt6WPS0BVyNfbuhJeT84l7uBuCBFzmNyfTRQ02D6Tqlri3wgGla03jfIR,fOmFAYqjsxj5KjnEwRMiI9t0fsdWZZlm7j2HsLNtPi48lMisogD8xe1KNCntQeiaIVKODiXmFSoUsFB6hPKrdMNM0c8CZkKIY26Abbo8aayB2vmZyRWAuf1K6DTRuKARvROWlgU1LRPRkvacFmnNrIJC4x2j7pSSiYjqjHPAF1zmIdUezNcTUdVTrmzoDPw5Oe0GqJFKUpkwBawUWS4eihbj0nJCKkfvRftPqmlzi8soSGzb5JNBSU8IMrFecH1Q,esJHP8Az7SAJti1w0M7tSdh6ZIbUeNGsJT1229ajEsemBCV9SxY5QG41HSGL6ruzb1IYS1j9my040ZKb8ZjA12TtTq3ueyVCNQ8gMFZIPAVXoFt4I27jptMcfOGTpCSCO1uOZboZpe7WWveojT0pBNbEUUCv2I1xvdZuA964c2qKUeW5zDkHlHWnhNO7KVCL6zynHuhITVIEwv0vxfogJNQHACtISKadjkHIdmeAbJb5kpGveHxliLQtqyLiIf7X,L4MzNSNTXZxxnSARDdvQ0IgdtDJvH0Rg6TEwKx676l1ZFvSqWfwmWMPAtJJxD5qzHaAykb5l0BQeefHDVpEIW1qznsKWDDi7NsJ1X1nX3d8Bf6AVjW5G1vRJy9yzNYX4vaA1AdVgPUPROss1qUVJmyajegk0ed5tA9vXhJI7CdfZJDKKxXIyvaP1cV35L4RZ7EW4FOTkfglH5xxjef2qU7ZW1ORorUqDzUODQz95J3qtALeGe7NYFlRoVMV9qgR6,3VYw0jvtpeoAnJ7pzCXeWNIBw4yYzWV1R7bGva7CT4r2uO99XYAQ8CaZw94VQH6N3QSbZHwggIf22LUbZUMbSwbpYuEmXxXnwpx0ypSFbxOE2B0RBGgYL05pVdn0qGHhdGEiIWqzzwk6gduOYwcqPRR0K9JURSPYlFZQZdOMnEyeNG859OmkKXGSA2HXo4CVzGqVqeR41k8RBsvAwD9MsAlZaBfZXPAoHWEQtX72nhJGiOWY69pnyNgblfj3XjZV,0b3o3P773NelnagfmBV0YDiWUxHmPydGSxklulf6XD5m77tzT4FRJ5g2dMHaEeAmwfeM6UNxyogy9yq0ApYEmvhSoX8ae4CyohDgxHo5i1rq2OFZj1fEZLPypPPrhRBX3X3aGBnAQhQZKr4YtNrAYrhqsPRpBwdpC6zyPVBiJKrc5EOyObzI7MjHeIaVo3OujsUj4oe4LJPLpA8cLc12zqPWgFIGcsqNMAgUHUbhTnfFtCCGTar8Uofkaam1Lk5K,1VdNvnAKUJv3Rf1xHm6eFJen7Z9RJD75Wplvyn5Nm4aQaPYOSC1EIULyVseGEDnYbLkfguu7ZFm7F8FR0wsTPasTpCppF9qklZU19QQ1aRfpBpm8UKSWuvvrDQ2d0uvFGsis4c6GAUhCb5XmOA8gfj7uffP18YA6ZidyfBzhA5h1AbUxlvciCVyqDUcGy1WCmdGv3aOzjyWp6oX9Ap1aMH9XIXEUnBCLAWq1XH2HVI9NJmsNIWqQTej9YiF9GWPx,fOOnnQh97qBDqd4paW386dxc9i5t3XZM6T5R3VTgte5CH2A8iXgZdeXdL7V0yrEYxZhgzu3hTKYZVDaNT4vdab6vYppcUe2VuXaBdoS2PGMEubnbeftpjJamnxvSZj8QtymswIUVCMroXmwyO73zDCC8J0Rb3O2GqfrkOFebQkUhfWPDEVkWpWipR1cpwL4E5FIICE2qXjDFDe3NgdHKoaBNAnAcTQNtWpjvurLSWjeq7wDB5LsHt1MAhrbiwQWH,gQb7DleavpTwxrywy9qqojMgm7bSMjMR2pflOKcCKvGSN9gclEJ7yRIOQ6FK7pCt1ACxZgNQj17E59AOrdZJtokj7i1zhoN0SKB3LMszVwqvMZdciwUEIdUYxaVKRiNpG2pOiLRJ4JwpGKG22Xnk3JYQIktM8HVUjhnDQ1Bx3Kh8QcM8IWt27AAVm6xIBiR0OHA7MN7vAZ0dxtNcK3c4ERQbSJrXj92xnAj4fLRsl8snJfNAKKYde2pfbYeUtHU3,Aaxs9OM7UmZcSPvEC6OYaMU6g1QFlUIa84C8F7NSnC1Q1ksyWNsGk9sHytgIphyvGN0S50Helr5WwsxoeWGmkJcAb20GJbomZJK8zuG5TKBIYdQ4CdtZK3fJZ4Qfw5NkmAA3vZuYFNF8d3QS4Uy14xVW2Q7Femy248seLPXD8K59Sfl2GbOeti0h3CFDY2mgiIikIrVsImLU5HSUh0jLcQx3HH2RFhhfSsSkeL58hpGnol77LiQBctXAnvIRApFv,EYq0soXfCkNbCgCFb1Gc4mPTfKspGItBwervd64nFsJ3fUssBz19IiywRT3l8LIHAPI6OfeMTgRxoTyJZKoAuV4dTpL5Ro4Eufh8pIQxSfOSBB5kYd4gHSAfLhtoTt9o7Gvn7IJzs4Ob5wzJDB9fQ30SZwih3MFJJprbbez1Y1aV6NDVcURdn4fx52LFPulj2J2wNITcBtb5ZUGdbZyGjr5TqJNWZiDc5fLs84r6Wg0OJjwsx6EWv5CB2YFeFgSK,S87dNX0bhnRVZzEEifjMDY04mL4tLlhRroiZapK6QjRrJK53NentUcfb54I06nUXFeei9a0y47eHz1IgbNwYJ0Col2JdpeLUAVPBjAaZaHJVwKpcTCT2daUCz1d6ppOwjdgD7arx72yXt5cJp6cZNLOg48YENZub6w3wIj1z4zdplVx79X40BxqFvVv6ZoloqVkJH3wXZSsMivY5RDwGYYs1xX0ktf4L3bZVPUqWA17r99xUcJojToumuXnjeVlm,Sqr6M0Wj4cmkvf4dvv730PEK5pTkMrEjrqUia88uyRXTEBmndiJ59E2FTkbYNDWU9Jdqj9I3ws7OfHJYuA0uh3Wb5pALg7ql7AI8K7Jl6gSQAb7woqyerraMjFRIynj1KLbhhM1xxkkFPE9QrQ5wi38ziwvu3m5p311GoSwHSNiGIoKmAVFVra7YmRcV4N73KC4ZedcLCdTy0kZdd3m2WrwmvA2WwV4CcteLCTPLpIBLFNzObxVNY4cxe1R4od7f,224lFFdydTBSmegDE2O7bB3gZeZslhNaQvQke238NjC8aYMJrZ9E1TsfFdBi48y7aEVgF6CA3lSuktfrfZpkmJAx4QLOE4uwiDsmDnnk8NHYWAM2a7yxQwiT2R5Zc8SZqLx0c2nvnjqj0TjG1DtU6JGvlnGHAxdJGgrMLl4mJuk7SY024g3LQNWSAfZV3tCNdNrNBvqygGqQjLO1OjEtmbeyOhHnE7qexRmqbDcbjzcR4HHqfsXl8MSn09M6mFMj,SJAhJDJlpEzwhoFLjgrcelXb6CFpXwhYNEYW32LMf4GsBPkPDtM9266mFlE4YEUTqmh1QN2xdj2DS6lr20eNI191ZEvxTuXDnpumn1fVSbmj1kLFgFKOhFYuEqjdghtOISCo6FqAauWEBw8eVy9RLxqMKurnnpPIeHKcJCX4Or897NgGVmMh0JkjfSOdqxVB8d7Ji9PEf8pJcwia5l6Q7t7ZI5FtCGUYbh2YZ3Eg9dTCMnDMvuTwyL8kH3sN3lge,OmGIzG7mEZ1S31G1ak7lAhT2nDWclmqlUtaEXxjUO7iONqmeV4FVQ9RpmAtX0ELmv59ujlHksi8o2GdEfPyZkkqkIa4zuIveyDiOspPWUfBRE0kmxZSEPNyNYuA3fAQIlSPZxuIPfrtQg7njAIWalVcDR3Ow2lprLHRMbjrHgBecOmDjla9mnU4bqSoQrxoT9VJmw06xTOIslrYrklO76W48VjuQ6cz0fkTSwBbNnjBPNX5d3OjL1GtJ6Gh6kZMl,SxIl2vU18i6PsIZCb7Ew3eBBEJhuYoNSvnsyjVfHLanaL9XLfAQpUMJYSU2rPg3QJqChksFJxGyKIHLqrPUQCbfOEhYrh4wuuawJjKustr5RhFehXQhU59bGDsfAmwsDWhibM3JHKAcJljYFls08MoXRyepl0LDEaHmwEkxerlrkVdca3tsiPeVF9DKPgSmcTajox3nuNjC08VwwUb5NTJG7y6HYN0n0LVAZ8pXYlL9q8sPKNXXcOj9eNFQLkyKs,NYEOoMl6bqOmV6fVa3ZBZafinW9wXcy8aVnhem1jYxaYVk9vxroItlQB3gJZbcGgbvTyzSGXgWPxz7BkXNwezurC1El8v8BGxUmXx4bifZZrhLYBpqIcpAhAjxHHwxrS3M0ny5iRcrjRHb7E1R05b4wNhGlHOAfent9CH3vwUGdqgTmLs5lelVkKYAFThXVzJtUJWnGLPOJDhGRiwxZ4O9AaCDSZgkcmxOxhW9FkTrpZaA9SwnKv5ZXjG5ZImq6c,J8KqfiXmARayn4HBbvC5rB2NvS6lo7MbWG8MEvIz4UkIgQr2896WrZGGTh1QcyED9UXy916SLGKnZt8p9qcNomSsj1Ge9W8vAP4J4DtpmRJnqOHpoMEUWigIvnU9vHX2dtgoeMFHVUORdkjk7v5oKejCNk3PakRyjEhhyp7RqCUn9agPkNtECst5PS7E3Ri2kfRya6W3eFy1kA9JPIqc20xZsKJIMAMf0z96PvjkGAdDqsdXPoXe8bO0z32Lsq2k,LmYVX9pS0VNu5y2olPCs1gYBq8MjBi3kQcvIKzWfsJ6DmafR642jB2PeOQfQjhx7aeLlNJxWlgw2RXuVuyF1qvwxmrmncCBMtOXiH8Ld5UPDNF8iFjBZg5Gw50jm1Ejw7OODoOBT2J4k1MHC1pI3XaOkTouyDIjwp0aqwN2mGu5iKsSbYXYfoq3MGwwZn12WPyEpuaF3gFBbtVv3qP1vT92816ivJFw5i5MOJ2xfTbWVyeDAlI1pBR5XMJG1b7tK,ARGIjcQIsj1wZETSNjPoHMcWX41zD735GN0wbdhlszdfh7ZqgnztNbFZWTsuZ0K6UIrlFy4KemfTnVnGUYMZpA9U1jgLLc33unmdtc2GFD2JWhUVGc7clZy8xwGJwoJGHd8bcjFuSfk8xUvvkjfIIa2QTBHqsTWFNwzj0YeI6oVxlk9MX0C6bdxJHmjDWmsXGpGd89nPYe32Wfx2XWQiwnLNYQ6yyZ8NlZbmLTTNBHJQ0DYRfo54vQ7f0IVoNCUz,IFQn96toBT3eGELEgQPzGcCA2fShFnhmWOazZWlKdH2IELwik6rmyR4dKyxOmj8EoHJdOhFOkIqHanaeyTUTMgwJxPVb874jBNYwSlLfzRZmspeHarTqtopjOyTOBHZFGujBsKzpKcIpYvuimijjAZbeIDFaQCZHtvMpSqFyNZH2il6Zw4Mz8Cx5idTFxua6CsNJOO855sS7Po1aXgvQHnSrPg3fd6K2E7rTkQihNMEPa70oVHdB6WDrEz6Ivie2,yBzxpdLSu0cPLpaoPfHhUAokOGCBb7MucUIowOndDtRg9pdqnMOW67QO5zE8tvGbj3CfQVhjPao2xohxeliSW9B4DrKaWprMk5MjfaybphlE85EgSJbikcDMGmXkerZMsBPLsDXpt9Rj39kNH8LoAQaJWwDK6iVdKjs0soJw0Ps5VTj3OL7KsVnym9uYG7AAY9XNgycur1xsNSUIy2MeYWbKJk7teyod7fmH8QDsffBGXhG5YGPiGrUZZsnbPeRy,hswtXzlDZZQ7Hnbr3th2q56OsgsO8htGiw86tVXaWwBG4dwhfuJJpNoIW7K5F23JNxYYEyQTZuV1BCzQnrwL6Qk66vAoM1IfsXtBt6cmgpjgPzTKJlDgQH9MKoGgDL3g8YWCcYmFjKNVd4jkx9BzLXUgIjUDmQATJsFTHrRsCrULiaUgUvoEkle5zEYkGh27DUlbYaEDyvVo59N0GHYohdquybY9mbudiL5NR8ruTIBgxTOuYn4zEiusL0fAqdvQ,NKuNwg6Z7C1raxN6dSajlhMl9U9H3SEuevJ4CRzqaniB2KPAHOgxkEBnapszFwuZ1S5r0OTKyaWJt105MWU5eKvcIYShRdjIq5hB6IBwJdH59JNOZ32OO4GWEcurjRd8U4OyL4SCsLEKFXSz3UEbQrB1GJslVUExxxGMoWKxLvrQbjoG4ieiilM2jLUGkjYcj6BFGwVHbGd0FnagecEMlF0MYYxhNBv0nyUq7Msja8Q1vdLaoHP98QkRgUAHfjvt,JLo2Mh15zJ8V0E492j7na5kp9OnGTVFL5IGmMeetDV09OEFaYKuOlLVMufG8LgPV15pfd2DdPIRgBGJCkV3jj7pqqLrJNi2qTtaCeMOViijobOmBfNNprQx2EbHqP6S9ylDw3LK1o1CBX8AZSKi3bII22o0ec73M0lFKSiLhZiZmxRlWU7gNevQWlFkFJ7NQys2K04gb4338BzbfUMjNAJL25SnEOqSLCSee9R2THuFBcB2U8R6pOU76wJzlDJjz,2CRikwEKUp0buFJIdW57L25RRWqAuA8GL2hvbxfoU7i81sjggkaWrAKT2chQZ4r9z2dGi7Tmc0w4Lmt7kwZhgvlSyDZIw1cpkdcdc5TAM52F5bAqkr4JGtwkl9ZTSh3JZx5P6Nls0VcA0owcA8taGOu5vAjVstqpYV6OYuzBbaOjxbG494Eyw6mDR29bDObm7bB5If7t90dwJsNySq3bMZeRGlHu9qwOgwmQwoTfNQXt93tkI3ApWyCh26spC0LF,Js1n5SWKlynxhYmVdBPw7I7uj9pruwkB21s9sdLjU1TjjhJYGcm1kd8kjnWF6nKAnsLw53DX765j9tTndXCLwvgVmcxdrfv7wNjiEQ5unOJBBmwzXS5StIYFJspRLR0EH9CJXxGKMAKKZ31oI9ntZRNo9iWoOWnUxd1CssRFIozwfvEvmobbydtK1tJQxv8cE8oG0gY9WwLyNCJLAVj1xlbYO2DsLeDx010VQAODOaZVmSQzXbCyM4nviXwZm4jXojlNwGyTqOoyEQdGkpv0iiAvY64YG1mQYWvq0DgWJDNxGXgcM3eCUYCK2SiLrxKhxSbejusFTmCinRj6UGzFCZjGTEaeF0K3Oe1NlAjvLe0kRVpSj2wxVjiZFgcnFfntAp037hbEMHbFDOc7uO9jc29OMqBpkFN6lYVYNoCPUJZnVHddDG4qbdzHTyA0sg7Wdao60z8s7vItsw6rdWRdymHcXExiqBfnZ7D5v2S7DNAe6inckrMrunHN3y39bw2xxmQSGxNZBrc20I0SsMuHIM8FuuJrHNajKN0d1sMAhHzkzmDnpC6tV2MPd3V0eJlfygi9d8vmvy6QvVusRKz5cGPTHPZ2RFhVREK5WZZubeBCzbqRCEOoL9W0swjAOHtuuXt8ydQEQPt73ZPjRmAs4bsYEchd4mhYVWA34tYGf36m5QAIXtaUSHJJFu6Xcs4QHytHJ4N718kBcy0kk1RDD991i0PyNL8L1ngiJ1rgxR5HLnUohqN8V1C2gsUcaLNz,dlrLcGB2uOhTYd7Z8zgUNtXDu5qL5B6Byr1hnvgaXOQnKjqTfK68563zkVxafWDlspatw22nXIOrqfASogEzBKLfJM73ciFLCWGz2A8D4Clb91TZ2xOM7JkRCLAA7xRZyba3UU1mOHLkLKBuaVvMelzjKLa4v35SVp2nQlTcsG4VTn4IvNcgFffyBrcIijNkX9gyQnwMbpU3NdDJGl2ZNMypTOAiMYCjYqYPF1fuZEYNJvC5icnDGeR5tXXfw5BydXrPnj10tnmi9IS4lThrE1h3m3LTGmFxEIiSmFEkoF8VXJik4f87aTMYwXJtddB2DYm0hSIpggvl4K'
2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 12:41:28 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 7]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50436
,2017-07-14 12:41:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dZXPhAjypA3cTgqXmKmMfp1yxws9Bw3b","error":null,"portNumber":50436}'
,2017-07-14 12:41:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dZXPhAjypA3cTgqXmKmMfp1yxws9Bw3b', error: 'null', listeningPort: '50436''
,Connecting to the localhost:50436
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,Connected to the localhost:50436
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 7, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-14 12:41:30 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "27B2CA8B-3D18-4D1B-BBCA-23DEE60C715D", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 124 got the same data back
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 7]
,# teardown
,2017-07-14 12:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,12:41:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:8ABBC275-0A33-4834-8930-987F8EE3835A
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false,
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50436
[ThaliCore] Session.disconnect() peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
,# setup
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "05F6B8F2-51F6-437E-B02A-47E24E1B1558", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:A2D2B89B-DD8B-4639-A692-D9E61EEF0BA2
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6FD8DD74-6B76-4EAB-898D-37415969DCDD
[ThaliCore] Browser.startListening
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:41:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1383F40C-96B4-4A21-A631-CDF40A056,98D
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB1D2901-E973-4AA9-BB6A-4759081EBB4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB1D2901-E973-4AA9-BB6A-4759081EBB4A", generation: 0)
2017-07-14 12:41:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8ABBC275-0A33-4834-8930-987F8EE3835A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8ABBC275-0A33-4834-8930-987F8EE3835A", generation: 0)
2017-07-14 12:41:32 - DEBUG t,haliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB1D2901-E973-4AA9-BB6A-4759081EBB4A","generation":0}'
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabili,tyChangedEvent due to not being in started state'
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0,}]'
2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8ABBC275-0A33-4834-8930-987F8EE3835A","generation":0}'
,2017-07-14 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C9B187BB-C74A-4332-BEEC-8E80FFCFA986:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C9B187BB-C74A-4332-BEEC-8E80FFCFA986", generation: 0)
2017-07-14 12:41:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C9B187BB-C74A-4332-BEEC-8E80FFCFA986","generation":0}]'
2017-07-14 12:41:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C9B187BB-C74A-4332-BEEC-8E80FFCFA986","generation":0}'
2017-07-14 12:41:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1383F40C-96B4-4A21-A631-CDF40A05698D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1383F40C-96B4-4A21-A631-CDF40A05698D", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,12:41:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:41:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:38 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5BDEC6DB-2147-4F82-8C27-F1FFE3081A54
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "95639107-BDBB-4D7B-AF3B-4A4D9624E976", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:95639107-BDBB-4D7B-AF3B-4A4D9624E976
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,ok 139 discoveryActive should be false
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
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 146 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 12:41:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
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
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 12:41:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
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
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:7ec30c2e-c4a2-4318-9a9a-89bfb078bb69 error: startListeningNotActive
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kpd3DaDo5htFMvnGxOrbrw4inj0HNRMD","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7ec30c2e-c4a2-4318-9a9a-89bfb078bb69","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7ec30c2e-c4a2-4318-9a9a-89bfb078bb69","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 162 Should be able to call stopAdvertisingAndListening in tea,rdown
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6CF9F78C-A489-4CE3-9504-6A2CEF0E47B2
,[ThaliCore] Browser.startListening
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 No error on starting
,ok 164 Got null as expected
2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MpzBBLfCKxUxAPeFkJNp4VinZa7DiNq8","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
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
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EFA0CF1B-AEFF-4299-A479-648A98F47D2B
[ThaliCore] Browser.startListening
2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:41:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on star,ting
,ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:41:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 175 Should be able to call stopListeningForAdvertisements in teardown
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
2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:8f7f8a2f-3b93-44c2-988a-330bc1d603db
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 12:41:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-14 12:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in teardown
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
2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:41:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:41:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50442'
,ok 185 Should throw
,# teardown
,2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:46 - DEBUG createNativeListener: 'listening 50444'
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
2017-07-14 12:41:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50447'
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-14 12:41:47 - DEBUG createNativeListener: 'listening 50451'
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
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50456'
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
2017-07-14 12:41:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 12:41:48, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-14 12:41:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'listening 50460'
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
,2017-07-14 12:41:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50464'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 201 stream was closed
ok 202 incoming should survive
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
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50468'
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
,2017-07-14 12:41:49 - DEBUG createNativeListener: 'listening 50472'
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
,2017-07-14 12:41:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
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
,2017-07-14 12:41:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50524'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'listening 50528'
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
,2017-07-14 12:41:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 229 serversManager must not be null
,ok 230 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 231 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-14 12:41:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 12:41:56 - DEBUG createNativeListener: 'listening 50531'
,ok 232 port must be in range
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50532'
ok 233 second start should return same port
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'listening 50534'
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 234 we should be connected
,2017-07-14 12:41:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 235 now we are disconnected
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 12:41:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 12:41:57 - DEBUG createNativeListener: 'Native Server - close'
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
,listening on 50536
,ok 243 should be equal
,# teardown
,2017-07-14 12:41:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
2017-07-14 1,2:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 244 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC300130-5B0C-4E41-A003-41F0F159FE44
[ThaliCore] Browser.startListening
,2017-07-14 12:41:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:41:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:41:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 245 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83C7AA4,B-9036-4E41-8DBF-DDA2A5861AC2 (syncValue: LsHyiMAxv1hgITe6t2l04n3jlliQqj5m)'
2017-07-14 12:41:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
2017-07-14 12:42:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}'
2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66FCBB9A-2036-4526-9064-41C06DEDA815, (syncValue: X4m7goqIZzLnt0WbCYIan1Is4ZLn4m9B)'
2017-07-14 12:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66FCBB9A-2036-4,526-9064-41C06DEDA815:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Advertiser: session connected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[ThaliCore] Advertiser: session connected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50542
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LsHyiMAxv1hgITe6t2l04n3jlliQqj5m","error":null,"portNumber":50542}'
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LsHyiMAxv1hgITe6t2l04n3jlliQqj5m', error: 'null', listeningPort: '50542''
,2017-07-14 12:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LsHyiMAxv1hgITe6t2l04n3jlliQqj5m', error: 'null', listeningPort: '50542''
,2017-07-14 12:42:02 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'LsHyiMAxv1hgITe6t2l04n3jlliQqj5m', originalSyncValue: 'X4m7goqIZzLnt0WbCYIan1Is4ZLn4m9B''
,ok 246 should be equal
,ok 247 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50544
2017-07-14 12:42:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X4m7goqIZzLnt0WbCYIan1Is4ZLn4m9B","error":null,"portN,umber":50544}'
2017-07-14 12:42:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X4m7goqIZzLnt0WbCYIan1Is4ZLn4m9B', error: 'null', listeningPort: '50544''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,ok 248 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50542
,[ThaliCore] Session.disconnect() peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] BrowserMan,ager.disconnect peer:66FCBB9A-2036-4526-9064-41C06DEDA815
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore], TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50544
[ThaliCore] Session.disconnect() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Pee,r(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
2017-07-14 12:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 0)
,# setup
,# Multiple local http requests
,listening on 50546
,ok 249 should be equal
,ok 250 should be equal
,ok 251 should be equal
,# teardown
,2017-07-14 12:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49
,2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
2017-07-14 12:42:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2, (syncValue: 5D84Fd6CQCsKRYOHmbgRnzxukxGgk95K)'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}'
2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66FCBB9,A-2036-4526-9064-41C06DEDA815 (syncValue: HVk2YrezNLqytboXOW09UFcoCOb6FIKb)'
,2017-07-14 12:42:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
[ThaliCore] Advertiser: session connected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
[ThaliCore] Advertiser: session connected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50554
,2017-07-14 12:42:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5D84Fd6CQCsKRYOHmbgRnzxukxGgk95K","error":null,"portNumber":50554}'
,2017-07-14 12:42:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5D84Fd6CQCsKRYOHmbgRnzxukxGgk95K', error: 'null', listeningPort: '50554''
,2017-07-14 12:42:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5D84Fd6CQCsKRYOHmbgRnzxukxGgk95K', error: 'null', listeningPort: '50554''
,2017-07-14 12:42:08 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: '5D84Fd6CQCsKRYOHmbgRnzxukxGgk95K', originalSyncValue: 'HVk2YrezNLqytboXOW09UFcoCOb6FIKb''
,ok 254 should be equal
,ok 255 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50556
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HVk2YrezNLqytboXOW09UFcoCOb6FIKb","error":null,"portNumber":50556}'
,2017-07-14 12:42:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HVk2YrezNLqytboXOW09UFcoCOb6FIKb', error: 'null', listeningPort: '50556''
,ok 256 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50554
[ThaliCore] Session.disconnect,() peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:66FCBB9A-2036-4526-9064-41C06DEDA815
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50556
[ThaliCore] Session.disconnect() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket, error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCor,e,] Browser: session notConnected removed relay for Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,2017-07-14 12:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,[ThaliCore] Session.session(_:peer:didChange:) peer:72BF5322-2BE1-4356-B635-4EBC6052DD67 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,[ThaliCore] Session.session(_:peer:didChange:) peer:176B5A53-E1B9-4695-BE7A-233BFCE90948 state: connected -> notConnected
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F09C7E7-1F18-4ABA-9ED2-53A8539D5B49", generation: 1)
[ThaliCore] Session.deinit peer:176B5A53-E1B9-4695-BE7A-233BFCE90948
,ok 257 specific error should be returned
,# teardown
,ok 258 must be stopped
,# setup
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50558'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 261 no errors
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50559'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A44B6BF0-F6D5-4CE0-8C10-2B2BF451DD09
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'listening 50560'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF1A18E7-E802-44A1-BE12-523BD4FDA110", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BF1A18E7-E802-44A1-BE12-523BD4FDA110
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF1A18E7-E802-44A1-BE12-523BD4FDA110", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:BF1A18E7-E802-44A1-BE12-523BD4FDA110
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 269 must be stopped
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
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50563'
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
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'listening 50564'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1FE6EB50-6A77-47CE-9A94-81604FF00388
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA647DFF-CD2C-4344-9938-9EC38F795CC5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA647DFF-CD2C-4344-9938-9EC38F795CC5
,2017-07-14 12:42:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
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
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50567'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F7017E88-3B54-42D2-8988-21897689929B
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2F2F9FF2-02B6-48FA-988A-F75A55F636A6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2F2F9FF2-02B6-48FA-988A-F75A55F636A6
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'listening 50569'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A011FA3B-EC06-415B-BCED-38E3F13BB863
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E04D9F65-A791-43DC-91FA-FEACB093DF66", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E04D9F65-A791-43DC-91FA-FEACB093DF66
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 is stopped after calling stop
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
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-14 12:42:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:42:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50572'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2B82F453-0429-4BC5-B591-A91D24D5A2AE
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
,ok 303 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50573'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F9AF0E83-46C6-4175-BB70-FE5AECB7A6FF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F9AF0E83-46C6-4175-BB70-FE5AECB7A6FF
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 306 discoveryActive matches
,ok 307 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 308 discoveryActive matches
,ok 309 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50575'
,# teardown
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
2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'listening 50576'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9538ADED-727C-4B04-BF81-7F18F859F2D3
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB105E64-5250-4426-A525-642D03982494", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BB105E64-5250-4426-A525-642D03982494
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserManager.foundP,eerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 311 portNumber equal null
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 50578'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A25B447-0B97-4AF3-8976-F39B69238394
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D8A1E24E-AAA7-492E-9A14-1611985D239C
,2017-07-14 12:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 12:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":0}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66FCBB9A-2036-4526-9064-41C06DEDA815 (syncValue: Tebulpt2FBVPW3nejVqvOmrMQqrlHwav)'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
,2017-07-14 12:42:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
2017-07-14 12:42:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8A1E24E-AAA7-492E-9A14-1611985D239C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:66FCBB9A-2036-4526-9064-41C06DEDA815:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1)
[ThaliCore] Session.disconnect() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] Browser.br,owser(_:lostPeer:) lost peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83C7AA4B-9036-4E41-8D,BF-DDA2A5861AC2:1
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","generation":1}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
2017-07-14 12:42:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}]'
2017-07-14 12:42:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:25 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:25 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 12:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 12:42:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":true,"generation":1,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", generation: 1),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:66FCBB9A-2036-4526-9064-41C06DEDA815:1
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "66FCBB9A-2036-4526-9064-41C06DEDA815", genera,tion: 1)
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Tebulpt2FBVPW3nejVqvOmrMQqrlHwav","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Tebulpt2FBVPW3nejVqvOmrMQqrlHwav', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06D,EDA815","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"66FCBB9A-2036-4526-9064-41C06DEDA815","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:66FCBB9A-2036-4526-9064-41C06DEDA815
2017-07-14 12:42:29 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A1B452C7-1CA9-493B-B5D2-61CAF3066822 (syncValue: X5KCpHvNUdsxvjleZ5Fe1CTDGc2SkxiR)'
,2017-07-14 12:42:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
[ThaliCore] Advertiser: session connected Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2", generation: 1)
,2017-07-14 12:42:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}]'
,2017-07-14 12:42:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","generation":1}'
,2017-07-14 12:42:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83C7AA4B-9036-4E41-8DBF-DDA2A5861AC2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50584
,2017-07-14 12:42:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X5KCpHvNUdsxvjleZ5Fe1CTDGc2SkxiR","error":null,"portNumber":50584}'
,2017-07-14 12:42:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X5KCpHvNUdsxvjleZ5Fe1CTDGc2SkxiR', error: 'null', listeningPort: '50584''
,2017-07-14 12:42:33 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 7, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:33 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:42:33 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
,ok 314 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
,[ThaliCore] Session.session(_:peer:didChange:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
[ThaliCore] Session.startOutputStream(with:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 7, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:3,5 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 315 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50584
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 7, 15]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0 state: connected -> notConnected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] Browser: session notConnected Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 7]
[ThaliCore] Browser: session notConnected rem,oved relay for Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D8A1E24E-AAA7-492E-9A14-1611985D239C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:28370A2A-E219-4A5F-8A3C-00058FE10BD5
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'listening 50587'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44494DD4-12BC-4559-8F3E-EEA02B4449F7
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DA5319DB-DF7F-4F8F-AF8F-6468B727A931
,2017-07-14 12:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:42:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
2017-07-14 12:42:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:36 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
2017-0,7-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CB92173D-6293-4EBE-A0FB-A434DD62F620 (syncValue: b0FKDk8krHSPaj3NPSFa6slObnfYFDXr)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF30668,22", generation: 0)
2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0) new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}]'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA5319DB-DF7F-4F8F-AF8F-6468B727A931:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
2017-07-14 12:42:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:42:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:37 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0)
[ThaliCore] Session.disconnect() peer:CB92173D-629,3-4EBE-A0FB-A434DD62F620:0
2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}]'
2017-07-14 12:42:,42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","generation":0}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:CB92173D-6293-4EBE-A0FB-A434DD62F620:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CB92173D-6293-4EBE-A0FB-A434DD62F620", genera,tion: 0)
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b0FKDk8krHSPaj3NPSFa6slObnfYFDXr","error":"Connection could not be established","portNumber":null}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b0FKDk8krHSPaj3NPSFa6slObnfYFDXr', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CB92173D-6293-4EBE-A0FB-A434DD62F620","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:CB92173D-6293-4EBE-A0FB-A434DD62F620
,2017-07-14 12:42:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A1B452C7-1CA9-493B-B5D2-61CAF3066822 (syncValue: OnVk2mfFL3vGQwNUbChzv7RtepggscHp)'
,2017-07-14 12:42:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
[ThaliCore] Advertiser: session connected Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
[ThaliCore] Session.startOutputStream(with:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 7, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", genera,tion: 0)
2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OnVk2mfFL3vGQwNUbChzv7RtepggscHp","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:47 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'OnVk2mfFL3vGQwNUbChzv7RtepggscHp', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF,3066822","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:47 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:42:47 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 12:42:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFD7BC78-6165-4F86-9705-757C7CE0F24C (syncValue: cKzNKxwspQX76WcPKcXvHhzEwW1QtL2y)'
,2017-07-14 12:42:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A1B452C7-1CA9-493B-B5D2-61CAF3066822:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A1B452C7-1CA9-493B-B5D2-61CAF3066822", generation: 0)
2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}]'
2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","generation":0}'
,2017-07-14 12:42:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:42:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A1B452C7-1CA9-493B-B5D2-61CAF3066822","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50597
2017-07-14 12:42:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cKzNKxwspQX76WcPKcXvHhzEwW1QtL2y",,"error":null,"portNumber":50597}'
2017-07-14 12:42:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cKzNKxwspQX76WcPKcXvHhzEwW1QtL2y', error: 'null', listeningPort: '50597''
,2017-07-14 12:42:49 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 7, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:42:51 - DEBUG testUtils: 'Got response data'
2017-07-14 12:42:51 - DEBUG testUtils: 'Got end'
,ok 316 response body should match testData
ok 317 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:42:51 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 12:42:51 - INFO thaliMo,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingState,UpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 12:42:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on serv,er'
,ok 318 must be stopped
[ThaliCore] BrowserManager.disconnect peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50597
[Thali,Core] VirtualSocket.closeStreams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeS,treams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.dei,nit vsID:17 [1, 3, 7, 16]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer,(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 7]
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DA5319DB-DF7F-4F8F-AF8F-6468B727A931", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:F7E52BED-B2B5-4FE4-A2B1-5D74D7D0FA3F
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-14 12:42:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'listening 50599'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A70640C-9134-4850-92C0-7DC030DA6AFA
,[ThaliCore] Browser.startListening
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:67F286DC-98FD-4585-9BD1-6FD40C61789A
2017-07-14 1,2:42:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 12:42:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}]'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFD7BC78-6165-4F86-9705-757C7CE0F24C (syncValue: Z2LsKwJ7B1TYSR6PoWC0POP5NanSvuVH)'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67F286DC-98FD-4585-9BD1-6FD40C61789A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
2017-07-14 12:42:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-,4678-93BD-74D50507EA9B", generation: 0)
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:42:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:42:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:530434CD-FD42-4B00-B7B0-D62CAE9735F1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "530434CD-FD42-4B00-B7B0-D62CAE9735F1", generation: 0)
2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}]'
2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","generation":0}'
,2017-07-14 12:42:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:42:56 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"530434CD-FD42-4B00-B7B0-D62CAE9735F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", genera,tion: 0)
2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z2LsKwJ7B1TYSR6PoWC0POP5NanSvuVH","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:42:58 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Z2LsKwJ7B1TYSR6PoWC0POP5NanSvuVH', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7,CE0F24C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 12:42:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 12:42:58 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 12:42:58 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 12:42:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,ier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 12:42:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 12:42:58 ,- DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92 (syncValue: tcIeE4TMks6dizzAwVOMcxOMZgvW7yVy)'
,2017-07-14 12:42:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A
[ThaliCore] Advertiser: session connected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFD7BC78-6165-4F86-9705-757C7CE0F24C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFD7BC78-6165-4F86-9705-757C7CE0F24C", generation: 0)
2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}]'
2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","generation":0}'
,2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:01 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFD7BC78-6165-4F86-9705-757C7CE0F24C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50606
2017-07-14 12:43:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tcIeE4TMks6dizzAwVOMcxOMZgvW7yVy",,"error":null,"portNumber":50606}'
2017-07-14 12:43:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tcIeE4TMks6dizzAwVOMcxOMZgvW7yVy', error: 'null', listeningPort: '50606''
,2017-07-14 12:43:01 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 7, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:02 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:02 - DEBUG testUtils: 'Got end'
,ok 321 response body should match testData
,ok 322 must be started
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A
[ThaliCore] Session.startOutputStream(with:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 7, 18, 19]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
[ThaliCore] Advertiser: session connected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,[ThaliCore] Session.session(_:peer:didChange:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,[ThaliCore] Session.startOutputStream(with:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 7, 18, 19, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 12:43:09 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50606
[ThaliCore] VirtualSocket.clos,eStreams() vsID:18
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote p,eer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSo,cketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
,[ThaliCore] Session.session(_:peer:didChange:) peer:25CE863C-B9B2-414C-A6DF-F2C123B24601 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 7, 18, 19]
[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 7, 18]
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 7]
,[ThaliCore] Session.disconnect() peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB8AEFDF-8E8F-43B2-99C9-1B68A7B09E2A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "67F286DC-98FD-4585-9BD1-6FD40C61789A", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:25CE863C-B9B2-414C-A6DF-F2C123B24601
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:43:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 12:43:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 324 FIX ME, PLEASE!!!
,# teardown
,ok 325 must be stopped
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
,ok 326 must be stopped
,# setup
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 12:43:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 12:43:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 12:43:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
,2017-07-14 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 330 error should be null
ok 331 error should be null
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
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50610'
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
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 50611'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:62A6847E-B462-40C2-8B95-B49B4655AA11
,[ThaliCore] Browser.startListening
,2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 344 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1012162F-2335-4678-93BD-74D50507EA9B:0
ok 345 error should be null
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1012162F-2335-4678-93BD-74D50507EA9B", generation: 0)
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-14 12:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,# teardown
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}]'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","generation":0}'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}]'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1012162F-2335-4678-93BD-74D50507EA9B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'listening 50612'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B6708255-20F7-4D95-AC9A-FA8C72110336", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B6708255-20F7-4D95-AC9A-FA8C72110336
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 351 error should be null
,ok 352 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B6708255-20F7-4D95-AC9A-FA8C72110336", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:B6708255-20F7-4D95-AC9A-FA8C72110336
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 353 error should be null
,ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 12:43:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'listening 50615'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 358 error should be null
ok 359 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
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
,ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 12:43:14 - DEBUG thaliMobileNativeWrapper: 'listening 50616'
ok 370 first call should succeed
ok 371 first call should succeed
ok 372 specific error should be returned
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
,2017-07-14 12:43:15 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 376 error should be null
,ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 12:43:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7bac8c1-c1c9-4e05-8789-0637a5f6a2f5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 382 should be called once
,ok 383 should not have been called more than once
,# teardown
,2017-07-14 12:43:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a7bac8c1-c1c9-4e05-8789-0637a5f6a2f5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6980a69c-0be7-441f-911d-db7f07db8291","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 392 peer should be available
,ok 393 cache contains native peer
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6980a69c-0be7-441f-911d-db7f07db8291","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 394 peer should be unavailable
,ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6f18e8ff-47d6-43e3-beb9-f4f0c9205bea","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 400 peer should be available
,ok 401 cache contains wifi peer
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6f18e8ff-47d6-43e3-beb9-f4f0c9205bea","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 402 peer should be unavailable
,ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
,ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d0944064-ad82-40e0-8992-c72a76177bdf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 407 first peer is available
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b05201d4-92c5-4be2-8ade-f178c7ef1106","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 second peer is available
,ok 409 first and second peers are different
,# teardown
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d0944064-ad82-40e0-8992-c72a76177bdf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b05201d4-92c5-4be2-8ade-f178c7ef1106","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-14 12:43:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fdd6c26-e900-4272-b1e7-11a1a7c10f8a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 peer is available
,# teardown
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9fdd6c26-e900-4272-b1e7-11a1a7c10f8a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7450902a-d909-40ae-acad-76e74e75396c","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 424 peer should be available
,2017-07-14 12:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7450902a-d909-40ae-acad-76e74e75396c","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 425 peer should be available
,ok 426 should store correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7450902a-d909-40ae-acad-76e74e75396c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50617'
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da037938-21e3-4c96-9669-d44a6adcf0a6","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da037938-21e3-4c96-9669-d44a6adcf0a6","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da037938-21e3-4c96-9669-d44a6adcf0a6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:18 - DEBUG thaliMobileNativeWrapper: 'listening 50618'
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e477f45-5d45-4c22-bcc4-c112c8fd2ce3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 discovered available peer
,ok 438 peer is available
,# teardown
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e477f45-5d45-4c22-bcc4-c112c8fd2ce3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b80a6ed4-1174-41a9-86dd-e1e6229defc9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 442 peer should be available
,2017-07-14 12:43:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b80a6ed4-1174-41a9-86dd-e1e6229defc9","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 443 peer should be unavailable
,ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50619'
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae0560ec-ff79-4de3-9051-f2043114ba17","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 448 first peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98640a37-fac6-4a2e-9b2e-d53548ea0f1c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 449 second peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98640a37-fac6-4a2e-9b2e-d53548ea0f1c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 450 peer became unavailable
,ok 451 it was wifi peer
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98640a37-fac6-4a2e-9b2e-d53548ea0f1c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 we found peer again
,ok 453 it was wifi peer
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98640a37-fac6-4a2e-9b2e-d53548ea0f1c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 454 peer became unavailable
,ok 455 it was wifi peer
,# teardown
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ae0560ec-ff79-4de3-9051-f2043114ba17","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 12:43:19 - DEBUG thaliMobileNativeWrapper: 'listening 50620'
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2614d82f-b483-4666-9b81-79f786111385","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 first peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e7899618-96cc-4c99-acd9-99aa53e6c734","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 463 second peer is expected to be available
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2614d82f-b483-4666-9b81-79f786111385","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-14 12:43:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e7899618-96cc-4c99-acd9-99aa53e6c734","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7740ad8-5af3-47cd-b7d7-256905e643d4","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 475 peer discovered first time does not have new address
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7740ad8-5af3-47cd-b7d7-256905e643d4","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 476 address has not been changed
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7740ad8-5af3-47cd-b7d7-256905e643d4","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 477 new port handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7740ad8-5af3-47cd-b7d7-256905e643d4","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 478 new host handled correctly
,2017-07-14 12:43:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7740ad8-5af3-47cd-b7d7-256905e643d4","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 479 newAddressPort is null for unavailable peers
,# teardown
,ok 480 error should be null
ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 12:43:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 483 error should be null
ok 484 error should be null
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
,ok 498 error should be null
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
ok 506 contains expected properties
ok 507 the same hos,tAddress
ok 508 the same portNumber
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 12:43:22 - DEBUG thaliMobileNativeWrapper: 'listening 50621'
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ffc7a10e-e1dd-4dfc-a692-1112e2868196","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-14 12:43:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ffc7a10e-e1dd-4dfc-a692-1112e2868196","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'listening 50622'
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45748197-f0e9-403b-843a-e64cf4b4b71d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:45748197-f0e9-403b-843a-e64cf4b4b71d
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 12:43:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45748197-f0e9-403b-843a-e64cf4b4b71d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 525 error should be null
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
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'listening 50623'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8B2D0A8-AC90-4022-BE4D-0BE962EF76F7
,[ThaliCore] Browser.startListening
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c0d4ce5d-2fa9-468a-aaf8-9dc4e4649841","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 542 Peer availabilities has one entry for our connection type
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f55d7fd5-027f-4d14-a6f7-bdc48e060172","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c0d4ce5d-2fa9-468a-aaf8-9dc4e4649841","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f55d7fd5-027f-4d14-a6f7-bdc48e060172","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:43:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
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
ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'listening 50624'
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40c20d6b-09f3-4e54-b5d4-855941e0af66","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 550 1
,ok 551 2
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f780a981-da29-4d77-a057-497dc8b5bfd4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"40c20d6b-09f3-4e54-b5d4-855941e0af66","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 12:43:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f780a981-da29-4d77-a057-497dc8b5bfd4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:43:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 12:43:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'listening 50625'
ok 558 error should be null
ok 559 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ECC53031-B0F7-42CA-96F9-B11DCF478A34
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 560 error should be null
ok 561 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F88746E-DCBC-4143-A067-419AE121C4CF
,[ThaliCore] Browser.startListening
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 562 error should be null
ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}]'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92 (syncValue: 0)'
,2017-07-14 12:43:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}]'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}]'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","generation":0}'
,2017-07-14 12:43:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:43:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ECC53031-B0F7-42CA-96F9-B11DCF478A34:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0)
[ThaliCore] Session.disconnect() peer:1C8CE36E-EC3,D-47B0-B0A5-661FC49CAF92:0
2017-07-14 12:43:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}]'
2017-07-14 12:43:,31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","generation":0}'
,2017-07-14 12:43:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 12:43:31 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92", genera,tion: 0)
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1C,8,CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","pee,rAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"portNumber":null,"re,created":true}'
,2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1A1FA89B-152B-41D0-B735-F1ABE32DB4DB (syncValue: 1)'
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:),
2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:43:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] Session.session(_:peer:didChange:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1A1FA89B-152B-41D0-B735-F1ABE32DB4DB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50631
,2017-07-14 12:43:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50631}'
,2017-07-14 12:43:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0E72115A-8DB3-42E8-94B5-C3755B9B7A1B (syncValue: 2)'
,2017-07-14 12:43:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1FA89B-152B-41D0-B735-F1ABE32DB4DB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 7, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:43:36 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:36 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E72115A-8DB3-42E8-94B5-C3755B9B7A1B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50635
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
,2017-07-14 12:43:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50635}'
,[ThaliCore] BrowserManager.disconnect peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92
,[ThaliCore] Session.session(_:peer:didChange:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:1C8CE36E-EC3D-47B0-B0A5-661FC49CAF92
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E72115A-8DB3-42E8-94B5-C3755B9B7A1B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 7, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] Session.startOutputStream(with:) peer:80413BE2-FDC0-4EF3-BBAE-DD50B8E1A4D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [1, 3, 7, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:43:39 - DEBUG testUtils: 'Got response data'
,2017-07-14 12:43:39 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] Advertiser: session connected Peer(uuid: "ECC53031-B0F7-42CA-96F9-B11DCF478A34", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
,[ThaliCore] Session.session(_:peer:didChange:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] Session.startOutputStream(with:) peer:34220E5A-8F40-4411-9054-05CFE8F1F788
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,4 [1, 3, 7, 21, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1A1FA89B-152B-41D0-B735-F1ABE32DB4DB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:43:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0E72115A-8DB3-42E8-94B5-C3755B9B7A1B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:43:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:43:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 7, 22, 23, 24]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:43:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:43:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:43:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket.closeS,treams() vsID:23
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeS,treams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 7, 22, 24]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 7, 22]
,ok 565 error should be null
,ok 566 error should be null
,# setup
,ok 567 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 12:43:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22,
[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 7]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketD,isconnectHandler
,# teardown
,ok 568 error should be null
ok 569 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 570 getPeerIdentifier
ok 571 getConnectionType
ok 572 getActionType
ok 573 getActionState
ok 574 getPskIdentity
ok 575 getPskKey
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
,2017-07-14 12:43:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 580 clean kill
ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 582 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 583 forever agent should have it's own destroy method
,ok 584 agent's destroy should be called
ok 585 agent's destroy should not be called again
ok 586 agent is destroyed
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
ok 627 first enqueue is fine
ok 628 is an agent
ok 629 second enqueue is fine
ok 630 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 631 Queue is empty
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
ok 638 enqueue worked
ok 639 is an agent
ok 640 enqueue 2 worked
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
,ok 650 wrong arg type
,ok 651 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 652 good enqueue
,ok 653 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 654 good enqueue
,ok 655 2nd good enqueue
,ok 656 we are in the pool
,ok 657 We are out of the pool
,ok 658 Action was killed
,ok 659 The original kill was called too
,ok 660 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 661 good enqueue
,ok 662 first kill
,ok 663 second NOOP kill
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
,2017-07-14 12:44:07 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
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
,ok 680 Got Null
ok 681 Got another null
2017-07-14 12:44:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 682 is an agent
2017-07-14 12:44,:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
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
ok 722 must return null after successful call
,# teardown
,2017-07-14 12:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 723 Response should be NETWORK_PROBLEM
ok 724 reject reason should be: Could not establish TCP connection
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
ok 738 Should be NETWORK_PROBLEM caused closing server socket
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
,ok 743 ecdh for local device cannot be null
,ok 744 milliseconds cannot be less than 0
,ok 745 milliseconds cannot be 0
,ok 746 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 747 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 748 should be equal
,ok 749 should be equal
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
,ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 761 should be equal
ok 762 should be equal
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
,# teardown
,# setup
,# validate generatePskSecret
,ok 768 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 769 Matching numbers
,ok 770 We have an entry!
ok 771 keys match
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
,ok 785 bluetooth peer's notification has correct connection type
,ok 786 tcp peer's notification has correct connection type
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-14 12:44:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 12:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 787 notification peer dictionary contains exactly 1 peer
,2017-07-14 12:44:30 - WARN thaliNotificationClient: 'peer is not available'
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
,ok 792 Peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 793 hostAddress must match
ok 794 portNumber must match
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
,ok 805 action should be resolved with NETWORK_PROBLEM error
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
,2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 811 peerDictionary should become empty
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 12:44:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 812 failed with expected error
ok 813 peer state should be RESOLVED
,# teardown
,2017-07-14 12:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 12:44:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 First action failed
,ok 815 second action killed
,# teardown
,2017-07-14 12:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 816 secrets are equal
,ok 817 Public key matches with the server key
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
,ok 828 Cache doesn't contain dictionary1
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
ok 845 should be 204
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
ok 850 not equal connection type
ok 851 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-14 12:44:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 852 First start and on called correctly
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
ok 895 All tests passed!
,# teardown
,2017-07-14 12:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-14 12:45:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 896 should be equal
,ok 897 All tests passed!
,# teardown
,2017-07-14 12:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-14 12:45:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-14 12:45:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 898 action should be killed
,ok 899 Error should be timed out
,ok 900 No doc found
,# teardown
,2017-07-14 12:45:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-14 12:45:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-14 12:45:08 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 901 should be equal
,2017-07-14 12:45:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-14 12:45:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
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
ok 906 Same pouchdB
,ok 907 same localDbName
ok 908 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-14 12:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'listening 50765'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:10B0CD6D-69F3-4A6F-93D9-C349008463B8
[ThaliCore] Browser.startListening
2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F31DA80D-5F19-4969-9F65-323952DF140D
,2017-07-14 12:45:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}]'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 3)'
,2017-07-14 12:45:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F31DA80D-5F19-4969-9F65-323952DF140D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50768
2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50768}'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 4)'
2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":50768}'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 5)'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":50768}'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9AD30652-AF46-462F-A2F8-6E33AB8997AB (syncValue: 6)'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9AD30652-AF46-462F-A2F8-6E33AB8997AB", generation: 0) found active relay
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":50768}'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 7)'
,2017-07-14 12:45:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Advertiser: session connected Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Advertiser: session connected Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 7, 25]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 7, 25, 26]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 7, 25, 26, 27]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 7, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 7, 25, 27, 28]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 7, 27, 28]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 7, 28]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 7, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 7, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 7, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 7, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 7, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 7, 28, 29, 30, 31, 33]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 7, 28, 29, 30, 31, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 7, 28, 29, 30, 31, 33]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 7, 28, 29, 30, 31, 33, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50781
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 7, 28, 29, 30, 31, 35]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 7, 28, 29, 30, 31, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 7, 28, 29, 30, 31, 36]
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":50781}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 8)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":50781}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 9)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":50781}'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 10)'
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":50781}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 7, 28, 29, 30, 31, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 7, 28, 29, 30, 31, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 7, 28, 29, 30, 31, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 7, 28, 29, 30, 31, 36, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 7, 28, 29, 30, 31, 36, 37, 38, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [1, 3, 7, 28, 29, 30, 31, 36, 38, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 7, 28, 29, 30, 31, 36, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 7, 28, 29, 30, 31, 36]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 7, 28, 29, 30, 31, 36, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.session(_:peer:didChange:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:peer:didChange:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937 state: connecting -> connected
,2017-07-14 12:45:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46, 47, 48]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46, 47, 48, 49]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 44, 46, 47, 48, 49, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 46, 47, 48, 49, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 46, 48, 49, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false,
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountere,d vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 46, 48, 49, 50, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 48, 49, 50, 51, 52]
[ThaliCore] TCPCl,ient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didS,ocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
,[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 48, 50, 51, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
,[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 50, 51, 52]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 51, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
,[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnecte,d
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-14 12:45:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 57]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD30652-AF46-462F-A2F8-6E33AB8997AB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 57, 58]
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-14 12:45:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 57, 59]
,2017-07-14 12:45:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 57, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 7, 28, 29, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 7, 28, 30, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 7, 28, 31, 36, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 7, 28, 36, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 7, 28, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61]
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
[ThaliCore] Session.startOutputStream(with:) peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 7, 28, 41, 42, 43, 52, 53, 54, 55, 56, 59, 60, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 7, 28, 41, 42, 43, 53, 54, 55, 56, 59, 60, 61, 62]
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 7, 28, 41, 42, 43, 54, 55, 56, 59, 60, 61, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 7, 28, 41, 42, 43, 54, 55, 59, 60, 61, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconn,ected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 7, 28, 41, 42, 43, 54, 55, 59, 61, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [1, 3, 7, 28, 41, 42, 43, 54, 55, 59, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socket,DidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] AdvertiserRelay.didCloseVirtualSoc,ketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 7, 28, 41, 42, 43, 54, 59, 61]
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] TCPClient.socketDidDiscon,nect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 7, 28, 41, 42, 43, 59, 61]
[ThaliCore] AdvertiserRelay.didSocketDisconnec,tHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 7, 28, 41, 42, 43, 61]
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDom,ain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] V,irtualSocket.deinit vsID:41 [1, 3, 7, 28, 42, 43, 61]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting,:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 7, 28, 43, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 7, 28, 61]
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 3, 7, 28]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9AD30652-AF46-462F-A2F8-6E33AB8997AB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:23 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 7]
,2017-07-14 12:45:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:45:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:45:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 909 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'listening 50809'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:430827BD-0DE6-4A3A-9F93-6F3DF46D2E1C
,[ThaliCore] Browser.startListening
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CBBF1823-F1CD-4A02-99F5-32B700AE83E7
,2017-07-14 12:45:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [1, 3, 7, 63]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [1, 3, 7, 63, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [1, 3, 7, 64]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [1, 3, 7, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [1, 3, 7, 64, 65, 66]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [1, 3, 7, 64, 65]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,7 [1, 3, 7, 64, 65, 67]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocal,izedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:,67
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [1, 3, 7, 64, 65]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 11)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":50781}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 12)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":50781}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 13)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [1, 3, 7, 64, 65, 68]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
,[ThaliCore] VirtualSocket.deinit vsID:68 [1, 3, 7, 64, 65]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [1, 3, 7, 64, 65, 69]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:69
[ThaliCore] VirtualSocket.deinit vsID:69 [1, 3, 7, 64, 65]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":50781}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] Session.startOutputStream(with:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [1, 3, 7, 64, 65, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:70
,[ThaliCore] VirtualSocket.deinit vsID:70 [1, 3, 7, 64, 65]
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 14)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":50781}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","generation":0}'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [1, 3, 7, 64, 65, 71]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 15)'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [1, 3, 7, 64, 65, 71, 72]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:71
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:71
[ThaliCore] VirtualSocket.deinit vsID:71 [1, 3, 7, 64, 65, 72]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:72
[ThaliCore] VirtualSocket.closeStreams() vsID:72
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:72,
[ThaliCore] VirtualSocket.deinit vsID:72 [1, 3, 7, 64, 65]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.di,dSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [1, 3, 7, 64, 65, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:73
,[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [1, 3, 7, 64, 65, 73, 74]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
,[ThaliCore] VirtualSocket.deinit vsID:73 [1, 3, 7, 64, 65, 74]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay,.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:74
,[ThaliCore] VirtualSocket.deinit vsID:74 [1, 3, 7, 64, 65]
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-14 12:45:25 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:722F6A08-FE12-4728-9A39-9E5301A535C8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F31DA80D-5F19-4969-9F65-323952DF140D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Session.deinit peer:E545EC0D-0ABE-4423-B60C-2395509F5937
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Advertiser: session connected Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
[ThaliCore] Session.session(_:peer:,didChange:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","generation":0}]'
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBBF1823-F1CD-4A02-99F5-32B700AE83E7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
,2017-07-14 12:45:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 12:45:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50824
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":50824}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 16)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":null,"portNumber":50824}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 17)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":n,ull,"portNumber":50824}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD9A9580-4877-495F-9C40-3FEB21F0DA73 (syncValue: 18)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DD9A9580-4877-495F-9C40-3FEB21F0DA73", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":50824}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 19)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"19","error":null,"portNumber":50781}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 20)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"20","error":null,"portNumber":50781}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 21)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) found active relay
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"21","error":null,"portNumber":50781}'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 22)'
,2017-07-14 12:45:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-,C8052C530F87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:75 [1, 3, 7, 64, 65, 75]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:76 [1, 3, 7, 64, 65, 75, 76]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:77 [1, 3, 7, 64, 65, 75, 76, 77]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:78 [1, 3, 7, 64, 65, 75, 76, 77, 78]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStre,amsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Advertiser: session connected Peer(uuid: "CBBF1823-F1CD-4A02-99F5-32B700AE83E7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:79 [1, 3, 7, 64, 65, 75, 76, 77, 78, 79]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:80 [1, 3, 7, 64, 65, 75, 76, 77, 78, 79, 80]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:81 [1, 3, 7, 64, 65, 75, 76, 77, 78, 79, 80, 81]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:79
[ThaliCore] VirtualSocket.closeStreams() vsID:79
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:79
,[ThaliCore] VirtualSocket.deinit vsID:79 [1, 3, 7, 64, 65, 75, 76, 77, 78, 80, 81]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[Tha,liCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:28 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:80
[ThaliCore] VirtualSocket.closeStreams() vsID:80
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:80
,[ThaliCore] VirtualSocket.deinit vsID:80 [1, 3, 7, 64, 65, 75, 76, 77, 78, 81]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:28 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:81
[ThaliCore] VirtualSocket.closeStreams() vsID:81
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:81
[ThaliCore] VirtualSocket.deinit vsID:81 [1, 3, 7, 64, 65, 75, 76, 77, 78]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_,:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-14 12:45:28 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:82 [1, 3, 7, 64, 65, 75, 76, 77, 78, 82]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,3 [1, 3, 7, 64, 65, 75, 76, 77, 78, 82, 83]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E27,05-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:84 [1, 3, 7, 64, 65, 75, 76, 77, 78, 82, 83, 84]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,5 [1, 3, 7, 64, 65, 75, 76, 77, 78, 82, 83, 84, 85]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:75
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:75
,[ThaliCore] VirtualSocket.deinit vsID:75 [1, 3, 7, 64, 65, 76, 77, 78, 82, 83, 84, 85]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:76
,[ThaliCore] VirtualSocket exited RunLoop vsID:76
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:76 [1, 3, 7, 64, 65, 77, 78, 82, 83, 84, 85]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:77
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:77
,[ThaliCore] VirtualSocket.deinit vsID:77 [1, 3, 7, 64, 65, 78, 82, 83, 84, 85]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:78
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:78
,[ThaliCore] VirtualSocket.deinit vsID:78 [1, 3, 7, 64, 65, 82, 83, 84, 85]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD9A9580-4877-495F-9C40-3FEB21F0DA73:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:86 [1, 3, 7, 64, 65, 82, 83, 84, 85, 86]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:85
[ThaliCore] VirtualSocket.closeStreams() vsID:85
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:85
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:85 [1, 3, 7, 64, 65, 82, 83, 84, 86]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] Session.startOutputStream(with:) peer:D04E2705-213F-47BC-B6DE-BDE92F4BFA0D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:87 [1, 3, 7, 64, 65, 82, 83, 84, 86, 87]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:82
[ThaliCore] VirtualSocket.closeStreams() vsID:82
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:82
[ThaliCore] VirtualSocket.deinit vsID:82 [1, 3, 7, 64, 65, 83, 84, 86, 87]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:83
[ThaliCore] VirtualSocket.closeStreams() vsID:83
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:83
,[ThaliCore] VirtualSocket.deinit vsID:83 [1, 3, 7, 64, 65, 84, 86, 87]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:84
[ThaliCore] VirtualSocket.closeStreams() vsID:84
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:84
,[ThaliCore] VirtualSocket.deinit vsID:84 [1, 3, 7, 64, 65, 86, 87]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adver,tiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0 state: notConnected -> connecting
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 910 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:86
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:86
,[ThaliCore] VirtualSocket.deinit vsID:86 [1, 3, 7, 64, 65, 87]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:87
[ThaliCore] VirtualSocket.closeStreams() vsID:87
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:87
,[ThaliCore] VirtualSocket.deinit vsID:87 [1, 3, 7, 64, 65]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] Session.disconnect() peer:E2889C1F-978,1-47EB-A87E-5FA42585CC92:0
[ThaliCore] Session.session(_:peer:didChange:) peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation,: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50781
[ThaliCore] Session.disconnect() peer:E2889C1F-9781-47EB-A87E-5FA42585CC92:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,2017-07-14 12:45:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}]'
,2017-07-14 12:45:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","generation":0}'
,2017-07-14 12:45:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 12:45:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:30 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:30 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:30 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:30 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50840
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"22","error":null,"portNumber":50840}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 23)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"23","error":null,"portNumber":50840}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 24)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24","error":null,"portNumber":50840}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 91E9A4F1-A2DD-4788-9B80-C8052C530F87 (syncValue: 25)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "91E9A4F1-A2DD-4788-9B80-C8052C530F87", generation: 0) found active relay
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"25","error":null,"portNumber":50840}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 26)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:88 [1, 3, 7, 64, 65, 88]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8,9 [1, 3, 7, 64, 65, 88, 89]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"26","error":"Peer is unavailable","portNumber":null}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,0 [1, 3, 7, 64, 65, 88, 89, 90]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable,":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 27)'
2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-,5FA42585CC92", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9,1 [1, 3, 7, 64, 65, 88, 89, 90, 91]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"27","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 28)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E2889C1F-9781-47EB-A87E-5FA42585CC92 (syncValue: 29)'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2889C1F-9781-47EB-A87E-5FA42585CC92", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"29","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-14 12:45:31 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:92 [1, 3, 7, 64, 65, 88, 89, 90, 91, 92]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:93 [1, 3, 7, 64, 65, 88, 89, 90, 91, 92, 93]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9,B80-C8052C530F87:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:94 [1, 3, 7, 64, 65, 88, 89, 90, 91, 92, 93, 94]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
[ThaliCore] Virtu,alSocket.init(inputStream:outputStream:) vsID:95 [1, 3, 7, 64, 65, 88, 89, 90, 91, 92, 93, 94, 95]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 12:45:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2889C1F-9781-47EB-A87E-5FA42585CC92","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:E2889C1F-9781-47EB-A87E-5FA42585CC92
,[ThaliCore] BrowserManager.disconnect peer:E2889C1F-9781-47EB-A87E-5FA42585CC92
,[ThaliCore] BrowserManager.disconnect peer:E2889C1F-9781-47EB-A87E-5FA42585CC92
,[ThaliCore] BrowserManager.disconnect peer:E2889C1F-9781-47EB-A87E-5FA42585CC92
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:92
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:92
,[ThaliCore] VirtualSocket.deinit vsID:92 [1, 3, 7, 64, 65, 88, 89, 90, 91, 93, 94, 95]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:93
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:93
,[ThaliCore] VirtualSocket.deinit vsID:93 [1, 3, 7, 64, 65, 88, 89, 90, 91, 94, 95]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:89
[ThaliCore] VirtualSocket.closeStreams() vsID:89
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:89
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:89 [1, 3, 7, 64, 65, 88, 90, 91, 94, 95]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:90
[ThaliCore] VirtualSocket.closeStreams() vsID:90
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:90
[ThaliCore] VirtualSocket.deinit vsID:90 [1, 3, 7, 64, 65, 88, 91, 94, 95]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:91
[ThaliCore] VirtualSocket.closeStreams() vsID:91
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:91
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:91 [1, 3, 7, 64, 65, 88, 94, 95]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:88
[ThaliCore] VirtualSocket.closeStreams() vsID:88
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
[ThaliCore] Session.startOutputStream(with:) peer:648234A4-5567-4B77-AEDF-D1DCB6E0B4B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:96 [1, 3, 7, 64, 65, 88, 94, 95, 96]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:88
[ThaliCore] VirtualSocket.deinit vsID:88 [1, 3, 7, 64, 65, 94, 95, 96]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:94
,[ThaliCore] VirtualSocket exited RunLoop vsID:94
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:94 [1, 3, 7, 64, 65, 95, 96]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:95
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:95
[ThaliCore] VirtualSocket.deinit vsID:95 [1, 3, 7, 64, 65, 96]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91E9A4F1-A2DD-4788-9B80-C8052C530F87:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:97 [1, 3, 7, 64, 65, 96, 97]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:96
[ThaliCore] VirtualSocket.closeStreams() vsID:96
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:96
[ThaliCore] VirtualSocket.deinit vsID:96 [1, 3, 7, 64, 65, 97]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 12:45:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-14 12:45:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 911 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:97
,[ThaliCore] VirtualSocket exited RunLoop vsID:97
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:97 [1, 3, 7, 64, 65]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DD9A9580-4877-495F-9C40-3FEB21F0DA73","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"91E9A4F1-A2DD-4788-9B80-C8052C530F87","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-14 12:45:32 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [1, 3, 7, 64]
,2017-07-14 12:45:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:45:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:45:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 912 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 913 should throw
,ok 914 should throw
,ok 915 (unnamed assert)
,ok 916 (unnamed assert)
,ok 917 (unnamed assert)
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
,ok 924 should be equal
,ok 925 should throw
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
,2017-07-14 12:45:38 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,ok 990 verify failed
,ok 991 constructor called once
,ok 992 constructor called with right args
,ok 993 start before stop
,ok 994 We got at least 3 calls to start
,ok 995 at least 3
,ok 996 default 1
,ok 997 1 run
,ok 998 default 2
,ok 999 2 run
,ok 1000 default 3
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
,2017-07-14 12:45:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 1030 Got socket hang up
,# teardown
,2017-07-14 12:45:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-14 12:45:52 - DEBUG localSeqManager: 'Got an error trying to update seq []'
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
,2017-07-14 12:45:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/4,98A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/498A8BF4-,5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
    at module.exports@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/4,98A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/498A8BF4-,5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
,2017-07-14 12:46:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-14 12:46:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-14 12:46:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1063 expressPouchDB was called once
,ok 1064 expressPouchDB was called with 2 arguments
,ok 1065 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1066 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1067 PouchDB was called once
,ok 1068 PouchDB was called with 1 arguments
,ok 1069 PouchDB was called with 'dbName' as 1-st argument
,ok 1070 ThaliSendNotificationBasedOnReplication was called once
,ok 1071 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1072 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1073 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1074 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1075 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1076 ThaliPullReplicationFromNotification was called once
,ok 1077 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1078 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1079 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1080 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1081 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1082 Salti was called once
,ok 1083 Salti was called with 4 arguments
,ok 1084 Salti was called with 'dbName' as 1-st argument
,ok 1085 Salti was called with 'acl' as 2-st argument
,ok 1086 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1087 Salti was called with 'options' as 4-st argument
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 50920'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A2678BD-F2AA-48E9-9779-C5C159F12A76
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:17 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "07C1F73D-C7DD-4F96-ADF9-A4163422A932", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:07C1F73D-C7DD-4F96-ADF9-A4163422A932
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 12:46:17 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1088 ThaliMobile.start was called once
,ok 1089 ThaliMobile.start was called with 3 arguments
,ok 1090 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1091 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1092 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1093 ThaliMobile.startListeningForAdvertisements was called once
,ok 1094 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1095 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1096 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1097 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1098 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1099 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1100 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1101 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 1102 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-14 12:46:17 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 12:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50922'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:76DC286B-7652-4097-BDCD-78C6FEFA27D5
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B08AD187-86D4-414B-8DBB-3665C2C223F7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B08AD187-86D4-414B-8DBB-3665C2C223F7
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
,ok 1149 ThaliMobile.stop was called once
,ok 1150 ThaliMobile.stop was called with 0 arguments
,ok 1151 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1152 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1153 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1154 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-14 12:46:18 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50924'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A997DC6-5F79-440A-9450-794BC05AAFAD
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F78180E-D722-46D7-9040-A78BEAED2BFF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F78180E-D722-46D7-9040-A78BEAED2BFF
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
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50926'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7A9FCED6-CAF3-4C93-9A59-46920F4D7265
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C180AE3-D39E-4249-850E-72E604BBC21F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9C180AE3-D39E-4249-850E-72E604BBC21F
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
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 50928'
,2017-07-14 12:46:18 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3FF7E83A-36D1-4759-A9A7-7BB1F665E269
,[ThaliCore] Browser.startListening
,2017-07-14 12:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 12:46:19 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABE94451-3F3A-471A-8015-60DEB4E8FAF8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ABE94451-3F3A-471A-8015-60DEB4E8FAF8
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 12:46:19 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-14 12:46:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 12:46:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 12:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 12:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
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
,2017-07-14 12:46:20 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:279:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-,C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,14 12:46:20 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-14 12:49:21 - DEBUG CoordinatedClient: 'test client failed'
2017-07-14 12:49:21 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Appli,cation/498A8BF4-5CDA-499B-B428-C83E659CF141/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-14 12:49:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
