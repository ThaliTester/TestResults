#### Test 113351851520d16b_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/65EAC8CE-F8E9-4D7D-899D-2BD6E2AA0658/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/65EAC8CE-F8E9-4D7D-899D-2BD6E2AA0658/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55187"
,(lldb)     command script import "/tmp/65EAC8CE-F8E9-4D7D-899D-2BD6E2AA0658/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:28:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:err,orHandler:) Peer(uuid: "A2E742DE-DF45-468A-B4F4-944F9BA578F4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A2E742DE-DF45-468A-B4F4-944F9BA578F4
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B0613EEA-08A8-480F-A211-C2CB037143A3
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3950DC40-8144-4028-AFF3-C7847A748952
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09267DE8-9565-4124-AB7B-2DDB90A52122", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:09267DE8-9565-4124-AB7B-2DDB90A52122
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09267DE8-9565-4124-AB7B-2DDB90A52122:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09267DE8-9565-4124-AB7B-2DDB90A52122", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-08-01 11:28:06 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.722263038158417
,2017-08-01 11:28:06 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-08-01 11:28:06 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:09267DE8-9565-4124-AB7B-2DDB90A52122:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "09267DE8-9565-4124-AB7B-2DDB90A52122", generation: 0)
,2017-08-01 11:28:10 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-01 11:28:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-01 11:28:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-01 11:28:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-01 11:28:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-01 11:28:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-01 11:28:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-01 11:28:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-01 11:28:14 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-01 11:28:14 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-01 11:28:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-08-01 11:28:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-01 11:28:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
2017-08-01 11:28:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in ,the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-08-01 11:28:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 51 participant data matches
,ok 52 test participant has uuid
,ok 53 participant data matches
,ok 54 test participant has uuid
,ok 55 participant data matches
,ok 56 own UUID is found from the participants list
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
,2017-08-01 11:29:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-01 11:29:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:99B28922-925F-4A3C-92FF-139652E77FBE
[ThaliCore] Browser.startListening
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-01 11:29:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C897B12C-BBF9-4AE6-9BC6-E72C61947BDB
[ThaliCore] Browser.startListening
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "971A4711-8449-4390-8C7C-E74E08A3FB4F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:971A4711-8449-4390-8C7C-E74E08A3FB4F
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:971A4711-8449-4390-8C7C-E74E08A3FB4F
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobil,e,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "216BB1EB-85FA-40F6-8E5F-C6E72FEAE677", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:216BB1EB-85FA-40F6-8E5F-C6E72FEAE677
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "216BB1EB-85FA-40F6-8E5F-C6E72FEAE677", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:216BB1EB-85FA-40F6-8E5F-C6E72FEAE677
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:216BB1EB-85FA-40F6-8E5F-C6E72FEAE677
,[ThaliCore] Advertiser.stopAdvertising() peerID:216BB1EB-85FA-40F6-8E5F-C6E72FEAE677
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:11 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3FF7A990-8C39-4FBC-B905-C091543C0B8F
2017-08-01 1,1:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C28DB0A8-E77A-47AA-B486-1CB80A6F3EF3
[Thali,Core] Browser.startListening
,2017-08-01 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E55A7F93-0665-4D1F-868C-2BDF896AC995:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E55A7F93-0665-4D1F-868C-2BDF896AC995", generati,on: 0)
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3FF7A990-8C39-4FBC-B905-C091543C0B8F
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2
2017-08-01 1,1:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A455AAE-1A56-4198-ABF8-0B2F78CDA907
[ThaliCore] Browser.startListening
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"607A023F-B618-46EF-94E2-E6C7B7C6028C","generation":0}'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 607A023F-B618-46EF-94E2-E6C7B7C6028C (syncValue: 3oByhmGK8QrR2aenAya01QplQrBWFAS7)'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68DB7C9D-F2A9-4988-BF01-ABC00BA349A9","generation":0}'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50857
,2017-08-01 11:29:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3oByhmGK8QrR2aenAya01QplQrBWFAS7","error":null,"portNumber":50857}'
,2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3oByhmGK8QrR2aenAya01QplQrBWFAS7', error: 'null', listeningPort: '50857''
,2017-08-01 11:29:17 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-08-01 11:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11,:,29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:607A023F-B618-46EF-94E2-E6C7B7C6028C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50857
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3oByhmGK8QrR2aenAya01QplQrBWFAS7","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A6D469B9-3E3F-424D-B89E-3EF03B482B87
2017-08-01 1,1:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Browser.startListening
2017-08-01 11:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:29:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
2017-08-01 11:29:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68DB7C9D-F2A9-4988-BF01-ABC00BA349A9","generation":0}'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68DB7C9D-F2A9-4988-BF01-ABC00BA349A9, (syncValue: OBY3zxwCP205axUputeYJ3cvy8E6Dgjs)'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA,349A9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found ,peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"607A023F-B618-46EF-94E2-E6C7B7C6028C","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F49BF619-EFCE-49AD-936B-BA7E264E926C","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
[ThaliCore] Advertiser: session connected Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:68DB7C9D-F2A9-4,988-BF01-ABC00BA349A9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] Browser: session ,notConnected retry count #3 for Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9 error: max retries exceeded
2017-08-0,1 11:29:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OBY3zxwCP205axUputeYJ3cvy8E6Dgjs","error":"Connection could not be established","portNumber":null}'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnect,Resolved -syncValue: 'OBY3zxwCP205axUputeYJ3cvy8E6Dgjs', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:29:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB57BA1F-0D18-4357-B930-5C8445B48464 (syncValue: RKL2Tyr,mHuYKa5SAeaTzViNC2KfxlKh0)'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB57BA1F-0D18,-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50864
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RKL2TyrmHuYKa5SAeaTzViNC2KfxlKh0","error":null,"portN,umber":50864}'
2017-08-01 11:29:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RKL2TyrmHuYKa5SAeaTzViNC2KfxlKh0', error: 'null', listeningPort: '50864''
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55 state: connecting -> connected
,Connecting to the localhost:50864
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
,[ThaliCore] Session.startOutputStream(with:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Connected to the localhost:50864
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,ok 88 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,2017-08-01 11:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:29:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A6D469B9-3E3F-424D-B89E-3,EF03B482B87
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:DB57BA1F-0D18-4357-B930-5C8445B48464
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50864
[ThaliCore] Session.disconnect() p,eer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
[ThaliCore] Advert,iserRelay.deinit
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] Session.deinit peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B83500FD-F735-4993-8A84-3B0EABFD7568
2017-08-01 1,1:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E6BCD6D7-48EB-4EC6-951B-A45AA706E119
[Thal,iCore] Browser.startListening
,2017-08-01 11:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
2017-08-01 11:29:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB57BA1F-0D18-4357-B930-5C8445B48464","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB57BA1F-0D18-4357-B930-5C8445B48464, (syncValue: 63BsUyOMxGWJsJOmgQdiGqioRqCYvTMI)'
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foun,dPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F49BF619-EFCE-49AD-936B-BA7E264E926C","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-,01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13783D87-45FF-4D17-B42B-A653E8B09DCB","generation":0}'
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
2017-08-01 11:29:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14E53D3B-100D-4C85-8359-22BD24E7A4CC","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B57BA1F-0D18-4357-B930-5C8445B48464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B57BA1F-0D18-4357-B930-5C8445B48464", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"63BsUyOMxGWJsJOmgQdiGqioRqCYvTMI","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:29:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '63BsUyOMxGWJsJOmgQdiGqioRqCYvTMI', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:29:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F49BF619-EFCE-49AD-936B-BA7E264E926C (syncValue: ucNw4WYVe83r00ELmxwDiNV,VZd7rEern)'
2017-08-01 11:29:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F49BF619-EFCE-49AD-936B-BA7E2,64E926C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ucNw4WYVe83r00ELmxwDiNVVZd7rEern","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ucNw4WYVe83r00ELmxwDiNVVZd7rEern', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-08-01 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13783D87-45FF-4D17-B42B-A653E8B09DCB (syncValue: AyfjQsTEwCEWwbGkeKcT0QGCDmSjqLPD)'
,2017-08-01 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50881
2017-08-01 11:29:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AyfjQsTEwCEWwbGkeKcT0QGCDmSjqLPD",,"error":null,"portNumber":50881}'
2017-08-01 11:29:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AyfjQsTEwCEWwbGkeKcT0QGCDmSjqLPD', error: 'null', listeningPort: '50881''
,Connecting to the localhost:50881
,Connecting to the localhost:50881
Connecting to the localhost:50881
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,Connected to the localhost:50881
,Connected to the localhost:50881
,Connected to the localhost:50881
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:50 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [3]
,ok 96 got the same data back
,# teardown
,2017-08-01 11:29:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B83500FD-F735-4993-8A84-3B0EABFD7568
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11,:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:13783D87-45FF-4D17-B42B-A653E8B09DCB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50881
[ThaliCore] Session.disconnect() p,eer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:709BCCF3-BC4B-4608-9082-D26EEC5531F5
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0D6ACF47-CE18-479A-A30B-1C93F4902313
[ThaliCore] Browser.startListening
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
2017-08-01 11:29:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13783D87-45FF-4D17-B42B-A653E8B09DCB","generation":0}'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13783D87-45FF-4D17-B42B-A653E8B09DCB, (syncValue: 7iGahPSAn2xHZP9Bizalhbx2WyoQ35ZZ)'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B,09DCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BCACD4FC-6BC5-40D6-9610-1040266CBCE0","generation":0}'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3119235A-AF7A-4ADD-9B55-A83D97083E39","generation":0}'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,3783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:13783D87,-45FF-4D17-B42B-A653E8B09DCB error: max retries exceeded
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7iGahPSAn2xHZP9Bizalhbx2WyoQ35ZZ","error":"Connection could not be established","portNumber":null}'
2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: '7iGahPSAn2xHZP9Bizalhbx2WyoQ35ZZ', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BCACD4FC-6BC5-40D6-9610-1040266CBCE0 (syncValue: cKQaqjlYMaCR75O9PB77sygfWjUWm9y1)'
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
[ThaliCore] Advertiser: session connected Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
[ThaliCore] Session.startOutputStream(with:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-08-01 11:30:09 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [3]
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50900
2017-08-01 11:30:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cKQaqjlYMaCR75O9PB77sygfWjUWm9y1",,"error":null,"portNumber":50900}'
2017-08-01 11:30:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cKQaqjlYMaCR75O9PB77sygfWjUWm9y1', error: 'null', listeningPort: '50900''
,Connecting to the localhost:50900
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:50900
2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-01 11:30:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3]
ok 99 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withErro,r:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,2017-08-01 11:30:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:709BCCF3-BC4B-4608-9082-D26EEC5531F5
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
,[ThaliCore] BrowserManager.disconnect peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50900
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cKQaqjlYMaCR75O9PB77sygfWjUWm9y1","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:08A37317-9245-4816-9BBA-BFF468DCB1A3
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:726A3B35-CA0E-4B9F-BE0E-7009616DE343
[ThaliCore] Browser.startList,ening
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:D08720CC-EAA5-4BF6-B697-407B5ADDB5F2
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
2017-08-01 11:30:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3119235A-AF7A-4ADD-9B55-A83D97083E39","generation":0}'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3119235A-AF7A-4ADD-9B55-A83D97083E39, (syncValue: SLNNJIh6tguWe55AFYrrJo7FxxbCmSIz)'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D970,83E39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}'
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7D1DD656-98E9-4642-8F1D-2B7D93F24C5C","generation":0}'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
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
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
2017-08-01 11:30:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13783D87-45FF-4D17-B42B-A653E8B09DCB","generation":0}'
2017-08-01 11:30:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:30:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31,19235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3119235A,-AF7A-4ADD-9B55-A83D97083E39 error: max retries exceeded
2017-08-01 11:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SLNNJIh6tguWe55AFYrrJo7FxxbCmSIz","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SLNNJIh6tguWe55AFYrrJo7FxxbCmSIz', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8C4149E0-9EF7-47F3-AF61-7B54D5101639 (syncValue: Eom5D72en8EG9syRwDA51kWGHPw4MWMB)'
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50916
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Eom5D72en8EG9syRwDA51kWGHPw4MWMB","error":null,"portNumber":50916}'
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Eom5D72en8EG9syRwDA51kWGHPw4MWMB', error: 'null', listeningPort: '50916''
,Connecting to the localhost:50916
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
Connected to the localhost:50916
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-01 11:30:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,ok 102 got the same data back
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:8 [3]
,# teardown
,2017-08-01 11:30:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:08A37317-9245-4816-9BBA-BFF468DCB1A3
,2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50916
[ThaliCore] Session.disconnect() p,eer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A5DCA84-7522-437C-8A57-CAB4F6E772FF
[ThaliCore] Browser.startListening
2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B1D08031-1F9F-45B6-A50C-99D850E180F5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B1D08031-1F9F-45B6-A50C-99D850E180F5
2017-08-01 1,1:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
,2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}]'
,2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}'
,2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D08031-1F9F-45B6-A50C-99D850E180F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D08031-1F9F-45B6-A50C-99D850E180F5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C", generation: 0)
2017-08-01 11:30:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C","generation":0}]'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C","generation":0}'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:34 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B1D08031-1F9F-45B6-A50C-99D850E180F5
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:30:34 - DEBUG thaliMobileNati,veWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-08-01 11:30:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0595C672-BD18-425F-A8BA-D3B9EE6AFA17
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpd,ateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2BCDA0F8-2AF1-410C-9F47-0180F1C87D3A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2BCDA0F8-2AF1-410C-9F47-0180F1C87D3A
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2BCDA0F8-2AF1-410C-9F47-0180F1C87D3A
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
2017-08-01 11:30:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-01 11:30:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-01 11:30:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-01 11:30:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-01 11:30:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-01 11:30:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-01 11:30:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:d71b10d1-caef-4480-bc73-fe81ed45ea61 error: startListeningNotActive
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZPea9yy3j9XlfFevER6XUz1gsMHjt0ld","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A6A8F23-15B4-4F2D-B910-164DE9C56977
[ThaliCore] Browser.startListening
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LEjzjDJin7cMFsjBOtv7OYtW8uCZs30w","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-08-01 11:30:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C92184C6-B902-43E3-BF36-081362D87285
,[ThaliCore] Browser.startListening
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:b5b86b64-b71c-4b1a-bbac-43ae333b89bc
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5DA9D523-DC1D-4083-847D-41E967413C38
[ThaliCore] Browser.startListening
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
2017-08-01 11:30:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A","generation":0}'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A, (syncValue: v3OTSEwCpyJa5OTVTRbHiBDCxjevTPZS)'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F58,1009A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
2017-08-01 11:30:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C8FCF81-7CEA-409B-B47C-33B13E726DA2","generation":0}'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:45 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50925
2017-08-01 11:30:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"v3OTSEwCpyJa5OTVTRbHiBDCxjevTPZS",,"error":null,"portNumber":50925}'
2017-08-01 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'v3OTSEwCpyJa5OTVTRbHiBDCxjevTPZS', error: 'null', listeningPort: '50925''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0) found active relay
,2017-08-01 11:30:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cv5ba1BOX2nkkMqsdY80S4p2dikLzI56","error":null,"portNumber":50925}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0) found active relay
,2017-08-01 11:30:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AQcYlZqn9Q1KboPxrSoItYJGRUTWImTh","error":null,"portNumber":50925}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253
[ThaliCore] Advertiser: session connected Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253
,[ThaliCore] Session.session(_:peer:didChange:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253
[ThaliCore] Session.startOutputStream(with:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
[ThaliCore] Advertiser: session connected Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
,[ThaliCore] Session.session(_:peer:didChange:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
[ThaliCore] Session.startOutputStream(with:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:30:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:30:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSoc,ketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] ,Advertiser.stopAdvertising() peerID:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserI,nfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] BrowserManager.disconnect peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A
[ThaliCore] AdvertiserRelay.didSocketDisconnectH,andler disconnecting:false
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50925
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted sock,et error:nil
[ThaliCore] VirtualSocket.deinit vsID:10 [3, 9, 11]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPListener.socketDidDisconnect(_:withErro,r:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:11 [3, 9]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vs,ID:9
[ThaliCore] Session.disconnect() peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket.deinit vsID:9 [3]
[ThaliCore] Session.deinit peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] BrowserRel,a,y.deinit
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:12ADFAEC-A5B8-44A3-B373-F08B523DE253 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
,[ThaliCore] Session.deinit peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
,# initial peer discovery
,2017-08-01 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-01 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-01 11:31:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-01 11:31:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-01 11:31:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-08-01 11:31:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-01 11:31:01 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:01 - DEBUG createNativeListener: 'listening 50930'
,ok 149 Should throw
,# teardown
,2017-08-01 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 50932'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 50935'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 50939'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 50944'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 50948'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 50952'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
2017-08-01 11:31:04, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 50956'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-08-01 11:31:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'listening 50960'
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
,ok 176 native server is nulled out
ok 177 native server should be closed
,ok 178 incoming has been removed
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
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-08-01 11:31:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:06 - DEBUG createNativeListener: 'listening 51012'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-01 11:31:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'listening 51016'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
,ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 51019'
ok 196 port must be in range
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 51020'
ok 197 second start should return same port
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 51022'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-08-01 11:31:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 51024
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5AE67C3A-6330-44AA-8E2E-D189F55382F0
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23
[ThaliCore] Browser.startListening
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
2017-08-01 11:31:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
2017-08-01 11:31:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817, (syncValue: GKn6RqHtOUbknRpJuq9yYmdYAowEShCH)'
2017-08-01 11:31:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4,C1817", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
[ThaliCore] Advertiser: session connected Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
2017-08-01 11:31:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9","generation":0}'
2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51029
,2017-08-01 11:31:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GKn6RqHtOUbknRpJuq9yYmdYAowEShCH","error":null,"portNumber":51029}'
,2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GKn6RqHtOUbknRpJuq9yYmdYAowEShCH', error: 'null', listeningPort: '51029''
,ok 210 should be equal
,2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9 (syncValue: 40FbPpCzfbmQIzgMtKkzXRZnCopUoZT1)'
,2017-08-01 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
,[ThaliCore] Session.session(_:peer:didChange:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51033
,2017-08-01 11:31:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"40FbPpCzfbmQIzgMtKkzXRZnCopUoZT1","error":null,"portNumber":51033}'
,2017-08-01 11:31:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '40FbPpCzfbmQIzgMtKkzXRZnCopUoZT1', error: 'null', listeningPort: '51033''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
[ThaliCore] Advertiser: session connected Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5AE67C3A-6330-44AA-8E2E-D189F55382F0
2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51029
[ThaliCore] Session.disconnect() peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51033
[ThaliCore] Session.disconnect() p,eer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
,[ThaliCore] Session.deinit peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:31:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 51035
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84056088-3896-48BB-8E52-4509E9BC57C6
[ThaliCore] Browser.startListening
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27,-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9, (syncValue: 72xg1q57byR93vtFv39meG8xGAJ9xOiG)'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:31:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"72xg1q57byR93vtFv39meG8xGAJ9xOiG","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:31:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '72xg1q57byR93vtFv39meG8xGAJ9xOiG', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:31:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:31:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817 (syncValue: ytyjtuNso1RgooFVH5lRUiR,tI3ElQ1I8)'
2017-08-01 11:31:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1,F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:31:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 ,11:31:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DD00B2C6,-79FA-4A27-BEDA-C0FD1F4C1817 error: max retries exceeded
2017-08-01 11:31:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ytyjtuNso1RgooFVH5lRUiRtI3ElQ1I8","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ytyjtuNso1RgooFVH5lRUiRtI3ElQ1I8', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:31:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2 (syncValue: gcA9BHX,hS7jFsFo1yQAT8ZeSAVuMByAa)'
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5DB0E0CB-D9D6,-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114
[ThaliCore] Advertiser: session connected Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51055
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gcA9BHXhS7jFsFo1yQAT8ZeSAVuMByAa","error":null,"portNumber":51055}'
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gcA9BHXhS7jFsFo1yQAT8ZeSAVuMByAa', error: 'null', listeningPort: '51055''
[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D91,14 state: connecting -> connected
,ok 217 should be equal
,ok 218 should be equal
ok 219 should be equal
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78615FF3-BB41-476C-AB03-7264399F5297 (syncValue: RGR7h6X1VeaWZSNE6qg0GkPr8FEN31QK)'
,2017-08-01 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:31:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51062
2017-08-01 11:31:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RGR7h6X1VeaWZSNE6qg0GkPr8FEN31QK",,"error":null,"portNumber":51062}'
2017-08-01 11:31:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RGR7h6X1VeaWZSNE6qg0GkPr8FEN31QK', error: 'null', listeningPort: '51062''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
[ThaliCore] Advertiser: session connected Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
,[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51055
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:78615FF3-BB41-476C-AB03-7264399F5297
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51062
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
,[ThaliCore] Session.deinit peer:78615FF3-BB41-476C-AB03-7264399F5297:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gcA9BHXhS7jFsFo1yQAT8ZeSAVuMByAa","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Session.deinit peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
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
,2017-08-01 11:31:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-01 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'listening 51066'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3DB05F67-8E45-463F-A761-E77B27B8AB8A
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'listening 51067'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9F5D32B-90A0-4B76-940B-37475DF48F96", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9F5D32B-90A0-4B76-940B-37475DF48F96
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9F5D32B-90A0-4B76-940B-37475DF48F96", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E9F5D32B-90A0-4B76-940B-37475DF4,8F96
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E9F5D32B-90A0-4B76-940B-37475DF48F96
[ThaliCore] Advertiser.stopAdvertising() peerID:E9F5D32B-90A0-4B76-940B-37475DF48F96
2017-08-01 11:31:52 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 233 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'listening 51070'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-01 11:31:53 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 51071'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBD32C90-0778-4ADD-9482-C75A634E9CBD
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "709284A4-8574-407B-8BD8-8EFFCE37786C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:709284A4-8574-407B-8BD8-8EFFCE37786C
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:709284A4-8574-407B-8BD8-8EFFCE37786C
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 51074'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF303307-8BCB-4816-BD2D-6E3F3EE3C242
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B4B034E-FDB5-496C-B0F0-609C73D07B34", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5B4B034E-FDB5-496C-B0F0-609C73D07B34
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5B4B034E-FDB5-496C-B0F0-609C73D07B34
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 51076'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2087F1F3-8219-4592-9724-1C9B1C055E52
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7DAB1EFB-DBDF-4669-9A6C-6BC746F7B4B0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7DAB1EFB-DBDF-4669-9A6C-6BC746F7B4B0
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7DAB1EFB-DBDF-4669-9A6C-6BC746F7B4B0
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
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
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-01 11:31:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
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
,2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-01 11:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-01 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-01 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-08-01 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-01 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-01 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# peer changes handled from a queue
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
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
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
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
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-01 11:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
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
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 51079'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2E2DB4B-2EBA-49BD-BD6D-6B99D03F099D
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 51080'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "422AFAB7-9BA3-48EF-826E-BAA0DC9673EF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:422AFAB7-9BA3-48EF-826E-BAA0DC9673EF
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:422AFAB7-9BA3-48EF-826E-BAA0DC9673EF
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 51082'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 51083'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4FAACB41-4F13-4BF4-AFE4-F7F5582ECBAC
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
2017-08-01 11:32:01 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}},)'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB72E643-E780-49C6-BEC0-4812224ED763", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CB72E643-E780-49C6-BEC0-4812224ED763
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 275 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:830B4368-4E9E-4860-A257-F1167467DB20:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "830B4368-4E9E-4860-A257-F1167467DB20", generation: 0)
,2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","generation":0}]'
,2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","generation":0}'
,2017-08-01 11:32:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB72E643-E780-49C6-BEC0-4812224ED763:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB72E643-E780-49C6-BEC0-4812224ED763", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B75A076C-9F54-42F5-AD10-23C35D30B52B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B75A076C-9F54-42F5-AD10-23C35D30B52B", generation: 0)
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","generation":0}]'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","generation":0}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CB72E643-E780-49C6-BEC0-4812224ED763
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:03 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:03 - DEBUG thaliMob,ileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:03 - DEBUG mak,e,IntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 277 must be stopped
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
,# can still do HTTP requests between peers with coordinator
,2017-08-01 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
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
,# calls correct starts when network changes
,2017-08-01 11:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 51085'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7EDC3305-B405-453E-BBDF-6FB61274F5F5
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78615FF3-BB41-476C-AB03-7264399F5297 (syncValue: CXpmQbA7fQSBmfVfLwkjQjQLe8OhAxIO)'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
2017-08-01 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}]'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A434C687-B492-4444-B453-FF485E320B98:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","generation":0}]'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}]'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}]'
2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
,2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:32:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
2017-08-01 11:32:09 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}]'
2017-08-01 11:32:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","generation":0}'
,2017-08-01 11:32:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:32:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78615FF3-BB41-476C-AB03-7264399F5297","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:78615FF3-BB41-476C-AB03-7264399F5297:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,8615FF3-BB41-476C-AB03-7264399F5297", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:32:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CXpmQbA7fQSBmfVfLwkjQjQLe8OhAxIO","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CXpmQbA7fQSBmfVfLwkjQjQLe8OhAxIO', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:32:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B1D3177E-372A-4F29-8F3A-5AC9E326B4C9 (syncValue: xIUF0dXmO3X1mJX9vNIGKf4,MtUlzqvms)'
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
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
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51093
2017-08-01 11:32:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xIUF0dXmO3X1mJX9vNIGKf4MtUlzqvms",,"error":null,"portNumber":51093}'
2017-08-01 11:32:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xIUF0dXmO3X1mJX9vNIGKf4MtUlzqvms', error: 'null', listeningPort: '51093''
,2017-08-01 11:32:15 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:15 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:15 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7EDC3305-B405-453E-BBDF-6FB61274F5F5
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-08-01 11:32:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51093
[ThaliCore] VirtualSocket.closeStr,eams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] Session.disconnect() peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:12 [3]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-08-01 11:32:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:32:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-01 11:32:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B75A076C-9F54-42F5-AD10-23C35D30B52B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B1D3177E-372A-4F29-8F3A-5AC9E326B4C9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'listening 51095'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 51096'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:49118CA1-48C3-4D56-B91F-1856981EA9C7
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
ok 305 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 51097'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "37411104-8B38-40FB-BCE7-5BAA23BEA8E9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:37411104-8B38-40FB-BCE7-5BAA23BEA8E9
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
,ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "37411104-8B38-40FB-BCE7-5BAA23BEA8E9", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:37411104-8B38-40FB-BCE7-5BAA23BEA8E9
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:37411104-8B38-40FB-BCE7-5BAA23BEA8E9
[ThaliCore] Advertiser.stopAdvertising() peerID:37411104-8B38-40FB-BCE7-5BAA23BEA8E9
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'listening 51100'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-01 11:32:21 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'listening 51101'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-01 11:32:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-01 11:32:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"769b6704-36ec-42e5-8e61-a4a4bd14e2c5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
ok 343 should not have been called more than once
,# teardown
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"769b6704-36ec-42e5-8e61-a4a4bd14e2c5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05d8878c-10a8-45a0-84a3-45d4f1db95cd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05d8878c-10a8-45a0-84a3-45d4f1db95cd","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6809070e-9386-41b2-b400-6134b9435f9f","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6809070e-9386-41b2-b400-6134b9435f9f","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9882a906-1181-4fdb-90fa-123c747371d6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f339538d-620b-4d41-b8ba-35a3bd041b38","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9882a906-1181-4fdb-90fa-123c747371d6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f339538d-620b-4d41-b8ba-35a3bd041b38","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c2f6a52-1a32-4c81-836b-fd33332a33fe","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 374 peer is available
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4c2f6a52-1a32-4c81-836b-fd33332a33fe","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-01 11:32:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-08-01 11:32:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7cdf7ea-8a09-4f91-8912-03b6641be6aa","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be ,available
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7cdf7ea-8a09-4f91-8912-03b6641be6aa","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 385 peer should be available
,ok 386 should store correct generation
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b7cdf7ea-8a09-4f91-8912-03b6641be6aa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 51102'
2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93f4fa87-093e-438c-b7c3-4d6de2d2df70","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93f4fa87-093e-438c-b7c3-4d6de2d2df70","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"93f4fa87-093e-438c-b7c3-4d6de2d2df70","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 51103'
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"125860e0-5886-404a-8919-41e2c307634b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered avai,lable peer
ok 398 peer is available
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"125860e0-5886-404a-8919-41e2c307634b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8c81bfe-4c49-455f-a858-6c228e0a27cd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 402 peer should be ,available
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8c81bfe-4c49-455f-a858-6c228e0a27cd","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 403 peer, should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'listening 51104'
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4f74fc0b-579b-49ed-9b80-815b7c57dbb8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"490e165e-be57-45eb-b40b-132aeaec23a6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"490e165e-be57-45eb-b40b-132aeaec23a6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"490e165e-be57-45eb-b40b-132aeaec23a6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"490e165e-be57-45eb-b40b-132aeaec23a6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4f74fc0b-579b-49ed-9b80-815b7c57dbb8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-08-01 11:32:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'listening 51105'
2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9aa004d2-1925-46ad-aeb8-509ccb9b6d81","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86a78de8-5998-49b9-bcf9-c2eaa2899f0a","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9aa004d2-1925-46ad-aeb8-509ccb9b6d81","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"86a78de8-5998-49b9-bcf9-c2eaa2899f0a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-08-01 11:32:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-08-01 11:32:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bac4190c-3447-4ec4-bf46-b79d88d59b3f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bac4190c-3447-4ec4-bf46-b79d88d59b3f","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bac4190c-3447-4ec4-bf46-b79d88d59b3f","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 437 new port handled correctly
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bac4190c-3447-4ec4-bf46-b79d88d59b3f","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 438 new host handled correctly
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bac4190c-3447-4ec4-bf46-b79d88d59b3f","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-08-01 11:32:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-08-01 11:32:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
,ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
,ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-08-01 11:32:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
,ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
ok 461 the same hostAddress
ok 462 the same portNumber
,# teardown
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 466 contains expected properties
ok 467 the same hos,tAddress
ok 468 the same portNumber
,# teardown
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 51106'
2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9c9b14d-e7ae-474f-93f0-d6aa27b8151a","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 472 Got specific error message
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9c9b14d-e7ae-474f-93f0-d6aa27b8151a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 51107'
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"79058e4b-f3d6-4cf7-85cf-af80f6ea0713","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:79058e4b-f3d6-4cf7-85cf-af80f6ea0713
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"79058e4b-f3d6-4cf7-85cf-af80f6ea0713","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-08-01 11:32:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
,ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-08-01 11:32:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
,ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-08-01 11:32:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-08-01 11:32:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-08-01 11:32:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'listening 51108'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:560A27BC-6DAC-45D2-94BE-264AB5AD7A3C
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0f335ce0-0c8f-4cfc-a57e-7074316c8ab2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"117f7409-d45a-4ace-b50f-a44abf5c88a7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0f335ce0-0c8f-4cfc-a57e-7074316c8ab2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"117f7409-d45a-4ace-b50f-a44abf5c88a7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'listening 51109'
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a7e6556-b4ae-4151-8436-52c22edd3272","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 1
,ok 511 2
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"90b59332-03df-4be9-bee6-ee9ff46e3d95","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0a7e6556-b4ae-4151-8436-52c22edd3272","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"90b59332-03df-4be9-bee6-ee9ff46e3d95","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-08-01 11:32:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'listening 51110'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ACA77010-5D8E-4A90-81AB-BD,F0C37999E5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ACA77010-5D8E-4A90-81AB-BDF0C37999E5
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] Browser.startListening
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
2017-08-01 11:32:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}]'
2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","generation":0}'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:38 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for FF233C22-60DB-4B1D-B6ED-7DC1227E0497 (syncValue: 0)'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
[ThaliCore] BrowserManager.foun,dPeerHandler peer:Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:32:38, - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","generation":0}]'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","generation":0}'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:32:38 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Advertiser: session connected Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3CE935A7-111C-47D8-8125-279181E75889 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51113
,2017-08-01 11:32:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":51113}'
,2017-08-01 11:32:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CA88F631-A53F-4016-997C-EACC85DE23E5 (syncValue: 1)'
,2017-08-01 11:32:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:41 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:41 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CE935A7-111C-47D8-8125-279181E75889 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [3, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51118
,2017-08-01 11:32:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":51118}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 13, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:44 - DEBUG testUtils: 'Got response data'
2017-08-01 11:32:44 - DEBUG testUtils: 'Got end'
ok 524 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] Advertiser: session connected Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] Session.startOutputStream(with:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [3, 13, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FF233C22-60DB-4B1D-B6ED-7DC1227E0497","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ACA77010-5D8E-4A90-81AB-BDF0C37999E5
2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-08-01 11:32:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-01 11,:32:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 525 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by re,mote peer})
ok 526 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler remove,d virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:14 [3, 13, 15, 16]
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] V,irtualSocket.deinit vsID:16 [3, 13, 15]
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [3, 13]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [3]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:ni,l
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-08-01 11:32:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
,ok 531 getConnectionType
,ok 532 getActionType
,ok 533 getActionState
,ok 534 getPskIdentity
,ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
ok 537 after start
2017-08-01 11:32:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-08-01 11:32:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 clean kill
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
,ok 545 agent's destroy should not be called again
,ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
,ok 549 Size must be 1
,ok 550 Entry counter must be 2
,ok 551 Entry exists
,ok 552 Size must be 2
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 3
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 4
,ok 559 Entry 1_1 should not be found
,ok 560 Entry 1_1 does not exist
,ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
,ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
,ok 575 Size should be MAXSIZE
,ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
,ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
,ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
,ok 593 good enqueue
,ok 594 Identity should match
,2017-08-01 11:33:03 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:33:03 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-08-01 11:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
ok 599 is an agent
,ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
,ok 602 start action is killed
,ok 603 killed action is still killed
,ok 604 enqueued action when stopped is killed
,ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
,ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
ok 610 wrong arg type
ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
,ok 615 2nd good enqueue
,ok 616 we are in the pool
,ok 617 We are out of the pool
,ok 618 Action was killed
,ok 619 The original kill was called too
,ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
,ok 622 first kill
,ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
,ok 625 2nd good enqueue
,ok 626 1st action is in the pool
,ok 627 2nd action is in the pool
,ok 628 1st action is out of the pool
,ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-08-01 11:33:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-08-01 11:33:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-01 11:33:06 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got null
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 638 is an agent
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-08-01 11:33:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-08-01 11:33:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 664 is an agent
ok 665 First does not throw
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 666 is an agent
ok 667 Second does not throw
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-08-01 11:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-08-01 11:33:10 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-08-01 11:33:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-08-01 11:33:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-08-01 11:33:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-08-01 11:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-08-01 11:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-08-01 11:33:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
,ok 689 Start after killed
,# teardown
,2017-08-01 11:33:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-08-01 11:33:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-08-01 11:33:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-08-01 11:33:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-08-01 11:33:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-08-01 11:33:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
,ok 701 ecdh for local device cannot be null
,ok 702 milliseconds cannot be less than 0
,ok 703 milliseconds cannot be 0
,ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
,ok 708 (unnamed assert)
,ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-08-01 11:33:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
,ok 720 good preAmble
,ok 721 good unencryptedKeyId
,ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
,ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
,ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
,ok 740 peerDictionalty contains 2 peers
,ok 741 bluetooth peer's notification has correct connection type
,ok 742 tcp peer's notification has correct connection type
,2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-01 11:33:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-08-01 11:33:29 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-08-01 11:33:29 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-01 11:33:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-08-01 11:33:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
ok 748 Peer state should be RESOLVED
,# teardown
,2017-08-01 11:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-08-01 11:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-08-01 11:33:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
ok 758 connectionType must match
ok 759 peerIds must match
,# teardown
,2017-08-01 11:33:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-08-01 11:33:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,ok 764 correct number of requests
,ok 765 correct number of failures
,ok 766 correct final peer state
,# teardown
,2017-08-01 11:33:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-08-01 11:33:37 - WARN thaliNotificationClient: 'peer is not available'
2017-08-01 11:33:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-08-01 11:33:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-08-01 11:33:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
,ok 769 peer state should be RESOLVED
,# teardown
,2017-08-01 11:33:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-08-01 11:33:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
,# teardown
,2017-08-01 11:33:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-08-01 11:33:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-08-01 11:33:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-08-01 11:33:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-08-01 11:33:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-08-01 11:33:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-08-01 11:33:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-01 11:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-01 11:33:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-08-01 11:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
,ok 806 not equal connection type
,ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-08-01 11:33:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-08-01 11:33:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
,ok 812 first action kill called
,ok 813 second action kill called
,ok 814 first cleared dictionary
,ok 815 first cleared pool
,ok 816 second cleared dictionary
,ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-08-01 11:33:51 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-08-01 11:33:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
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
,ok 845 right error
,# teardown
,2017-08-01 11:33:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-08-01 11:33:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-08-01 11:33:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-08-01 11:33:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-08-01 11:33:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-08-01 11:33:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-08-01 11:33:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-08-01 11:33:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-08-01 11:33:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-08-01 11:33:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:33:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:34:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
,ok 851 All tests passed!
,# teardown
,2017-08-01 11:34:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-08-01 11:34:02 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:34:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-08-01 11:34:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-08-01 11:34:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-01 11:34:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-01 11:34:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 854 action should be killed
,ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-08-01 11:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-08-01 11:34:10 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-08-01 11:34:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-01 11:34:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
,# teardown
,2017-08-01 11:34:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-08-01 11:34:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
,ok 863 same localDbName
,ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-08-01 11:34:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'listening 51246'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] Browser.startListening
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3C03286D-92EB-4924-A2C4-E042DE28FC9F
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 2)'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51249
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":51249}'
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 3)'
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Advertiser: session connected Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Advertiser: session connected Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [3]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0 state: notConnected -> connecting
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 18, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 18, 19, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [3, 18, 19, 20, 22]
,2017-08-01 11:34:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51258
,2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":51258}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 18, 19, 20, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.session(_:peer:didChange:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [3, 18, 19, 20, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [3, 18, 19, 20, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:23 [3, 18, 19, 20, 22, 24, 25]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 18, 19, 20, 22, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [3, 18, 19, 20, 22, 24, 26]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [3, 18, 19, 20, 22, 24, 26, 27]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [3, 18, 19, 20, 22, 26, 27]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 18, 19, 20, 22, 26, 27, 28]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 18, 19, 20, 22, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 18, 19, 20, 22, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 18, 19, 20, 22, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [3, 18, 19, 20, 22, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 18, 19, 20, 22, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Brows,erRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:18 [3, 19, 20, 22, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.deinit vsID:19 [3, 20, 22, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [3, 20, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 20, 26, 27, 28, 29, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 20, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [3, 20, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [3, 20, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [3, 20, 26, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [3, 20, 26, 28, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPListener.socketD,idDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:,) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) di,sconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[Th,aliCore] VirtualSocket.deinit vsID:26 [3, 20, 28, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [3, ,20, 28, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 20, 28, 31, 32, 34, 35, 36, 37]
[ThaliCore] A,dvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [3, 20, 28, 31, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disc,onnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [3, 20, 28, 31, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSoc,ketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [3, 20, 28, 31, 34, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil,
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [3, 20, 28, 31, 34, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [3, 20, 31, 34, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [3, 20, 34, 37, 38]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [3, 20, 34, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [3, 20, 34, 38, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3C03286D-92EB-4924-A2C4-E042DE28FC9F
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:34 [3, 20, 38, 39]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socke,t removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [3, 38, 39]
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:34:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:39
[ThaliCore] Virt,ualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [3, 38]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[Th,aliCore] VirtualSocket.deinit vsID:38 [3]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 865 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,0 [3, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=70 "Stale NFS file handle" UserInfo={NSLocalizedDescription=Stale NFS file handle, NSLocalizedFailureReason=Error in conn,ect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [3]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'listening 51277'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:638674DE-1248-425B-BB3C-67ABE1127ADB
[ThaliCore] Browser.startListening
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:89459276-EC79-4CF3-8003-7EC0263C9F17
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 4)'
[ThaliCore], BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":51258}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 5)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":51249}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 41, 42, 43]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [3, 41, 42, 43, 44]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [3, 41, 42, 44]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [3, 41, 42]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [3, 41, 42, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [3, 41, 42]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 6)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":51258}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [3, 41, 42, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [3, 41, 42]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket ,error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 7)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":51249}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [3, 41, 42, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [3, 41, 42, 47, 48]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [3, 41, 42, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [3, 41, 42]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket ,error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2B8EBEB4-F1B6-49B3-A042-2931850C5299","generation":0}]'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2B8EBEB4-F1B6-49B3-A042-2931850C5299","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2B8EBEB4-F1B6-49B3-A042-2931850C5299","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2B8EBEB4-F1B6-49B3-A042-2931850C5299","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2B8EBEB4-F1B6-49B3-A042-2931850C5299 (syncValue: 8)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Session.startOutputStream(with:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [3, 41, 42, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDe,scription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [3, 41, 42]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
[ThaliCore] Advertiser: session connected Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:89459276-EC79-4CF3-8003-7EC0263C9F17:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "89459276-EC79-4CF3-8003-7EC0263C9F17", generation: 0)
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","generation":0}]'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","generation":0}'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"68F79609-0A85-42F9-884E-51FBAC4E0541","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.deinit peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2B8EBEB4-F1B6-49B3-A042-2931850C5299", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51289
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":51289}'
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 9)'
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) found active relay
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":51258}'
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 10)'
2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
[ThaliCore] Session.startOutputStream(with:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'multiConn,ectResolved: {"syncValue":"10","error":null,"portNumber":51249}'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [3, 41, 42, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 68F79609-0A85-42F9-884E-51FBAC4E0541 (syncValue: 11)'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
2017-08-01 11:34:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68F79609-0A85-,42F9-884E-51FBAC4E0541", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
[ThaliCore] Session.init(session:identifier:connec,ted:notConnected:) peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [3, 41, 42, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [3, 41, 42, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
,[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [3, 41, 42, 50, 51]
,2017-08-01 11:34:29 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:50 [3, 41, 42, 51]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
[ThaliCore] Session.startOutputStream(with:) peer:E62D93A2-9949-43F9-985B-1E19C97A3BE1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [3, 41, 42, 51, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:51 [3, 41, 42, 53]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B8EBEB4-F1B6-49B3-A042-2931850C5299:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [3, 41, 42, 53, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [3, 41, 42, 54]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:51258
[ThaliCore] Session.disconnect() peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,2017-08-01 11:34:30 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
,2017-08-01 11:34:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-01 11:34:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 866 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [3, 41, 42]
,[ThaliCore] Session.deinit peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}]'
2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","generation":0}'
,2017-08-01 11:34:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:34:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E07BFCF8-CD88-4962-AAA9-802C74BFD5C1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:34:34 - WARN thaliNotificationClient: 'peer is not available'
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
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Connection could not be established","portNumber":null}'
,2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 12)'
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":51249}'
2,017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E07BFCF8-CD88-4962-AAA9-802C74BFD5C1 (syncValue: 13)'
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", g,e,neration: 0)
,[ThaliCore] Session.deinit peer:68F79609-0A85-42F9-884E-51FBAC4E0541:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:34:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
2017-08-,01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,2017-08-01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [3, 41, 42, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:,55 [3, 41, 42]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:40 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 14)'
2017-08-01 11:34:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
2017-08-01 11:34:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":51249}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [3, 41, 42, 56]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[Th,aliCore] VirtualSocket.deinit vsID:56 [3, 41, 42]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDis,connectHandler
,2017-08-01 11:34:41 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 15)'
2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":51249}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [3, 41, 42, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
,[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [3, 41, 42]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket ,error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:44 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51249
[ThaliCore] Session.disconnect() peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
,2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:34:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:34:45 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
2017-08-01 11:34:45 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
2017-08-01 11:34:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-01 11:34:45 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-01 11:34:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 16)'
2017-08-01 11:34:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:94,315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,4315540-88C1-4914-B493-B105D908F8AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
2017-08-01 11:34:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
2017-08-01 11:34:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-01 11:34:49 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01 11:34:49 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:94,315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,4315540-88C1-4914-B493-B105D908F8AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:34:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":"Peer is unavailable","portNumber":null}'
,2017-08-01 11:34:50 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] Session.deinit peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserRelay.deinit
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-08-01 11:39:26 - ERROR CoordinatedClient: 'test failed, name: 'Coordinated replication action test - should throw error when wrong remote db name is provided''
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
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
,2017-08-01 11:39:26 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - should throw error when wrong remote db name is provided, error: 'Error: test failed, name: 'Coordinated replication action test - should throw error when wrong remote db name is provided'', stack: 'CoordinatedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22,
tryCatcher@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/A,pplication/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/Tha,liTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/rel,ease/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-08-01 11:39:26 - ERR,OR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-08-01 11:39:26 - DEBUG CoordinatedClient: 'all tests completed'
,2017-08-01 11:41:26 - DEBUG CoordinatedClient: 'test client disconnected'
2017-08-01 11:41:26 - DEBUG CoordinatedClient: 'test client failed'
,2017-08-01 11:41:26 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_Coordinated replication action test - should throw error when wrong remote db name is provided_finished', test: 'Coordinated replica,tion action test - should throw error when wrong remote db name is provided'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.j,s:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/09D,A20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/s,o,cket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/,Application/09DA20E6-66B4-44AB-859E-CA63DFB5CB9C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-08-01 11:41:26 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
