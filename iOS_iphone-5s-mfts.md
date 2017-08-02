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
,(lldb) command source -s 0 '/tmp/FCF64737-A13C-4624-BC60-849A98EF0825/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/FCF64737-A13C-4624-BC60-849A98EF0825/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56964"
,(lldb)     command script import "/tmp/FCF64737-A13C-4624-BC60-849A98EF0825/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:33:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BBFE68AC-B6C7-492D-80,C3-302911B5052C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BBFE68AC-B6C7-492D-80C3-302911B5052C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9BC92E93-8797-4467-A42E-6FEFF987CAC1
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D3BBBFF-,1F7E-4F48-BA58-008EC223A52D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "714D736D-AC52-405D-8AAA-7153CBBA8CCD", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:714D736D-AC52-405D-8AAA-7153CBBA8CCD
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:714D736D-AC52-405D-8AAA-7153CBBA8CCD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "714D736D-AC52-405D-8AAA-7153CBBA8CCD", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-08-02 13:33:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
Total duration:  2.214101016521454
,2017-08-02 13:33:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-08-02 13:33:58 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:714D736D-AC52-405D-8AAA-7153CBBA8CCD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "714D736D-AC52-405D-8AAA-7153CBBA8CCD", generation: 0)
,2017-08-02 13:34:01 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-02 13:34:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-02 13:34:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-02 13:34:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-02 13:34:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-02 13:34:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-02 13:34:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-02 13:34:05 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-02 13:34:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-02 13:34:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-08-02 13:34:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-02 13:34:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
,# teardown
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
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
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
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-08-02 13:34:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-02 13:34:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B93E89E-97E3-41A2-9E96-45761413CD81
[ThaliCore] Browser.startListening
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CA1BD888-59A2-4C46-AF0A-761BFDE64DD5
,[ThaliCore] Browser.startListening
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-08-02 13:34:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "85C98BAB-C1C3-4915-82C9-FDD4C9BB4D04", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:85C98BAB-C1C3-4915-82C9-FDD4C9BB4D04
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:85C98BAB-C1C3-4915-82C9-FDD4C9BB4D04
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C03E0167-4F02-4384-860F-F9D8FF5ADDCC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C03E0167-4F02-4384-860F-F9D8FF5ADDCC
2017-08-02 13:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:04, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "C03E0167-4F02-4384-860F-F9D8FF5ADDCC", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:C03E0167-4F02-4384-860F-F9D8FF5ADDCC
2017-08-02 13:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingS,tateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:C03E0167-4F02-4384-860F-F9D8FF5ADDCC
[ThaliCore] Advertiser.stopAdvertising() peerID:C03E0167-4F02-4384-860F-F9D8FF5ADDCC
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:35:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1EECE896-6DA2-4ED3-9377-AA8EDCC67D79", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1EECE896-6DA2-4ED3-9377-AA8EDCC67D79
2017-08-02 1,3:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:130B47C2-2585-4779-BC3C-78BBC74BD435
[Thali,Core] Browser.startListening
2017-08-02 13:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:12 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15D5145B-E249-4A5F-B306-CF7DADB80079:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15D5145B-E249-4A5F-B306-CF7DADB80079", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED60016B-7091-44FC-9A9B-74EEA528D285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED60016B-7091-44FC-9A9B-74EEA528D285", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EECE896-6DA2-4ED3-9377-AA8EDCC67D79:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EECE896-6DA2-4ED3-9377-AA8EDCC67D79", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1EECE896-6DA2-4ED3-9377-AA8EDCC67D79
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18EAED4C-36F9-42F4-85C3-9F97B529CE7D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18EAED4C-36F9-42F4-85C3-9F97B529CE7D
2017-08-02 1,3:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B16DCEE6-EA4A-4C87-9E88-632FDE6C243A
[ThaliCore] Browser.startListe,ning
2017-08-02 13:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18EAED4C-36F9-42F4-85C3-9F97B529CE7D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18EAED4C-36F9-42F4-85C3-9F97B529CE7D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
2017-08-02 13:35:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"544E1963-72AB-4976-83C3-D98BB4166601","generation":0}'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 544E1963-72AB-4976-83C3-D98BB4166601 (syncValue: GuZV6MUSTXVJffYmBDZZKhxn7cmek1BD)'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54,4E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C550145-A750-4414-8AE2-913CC31E1F62","generation":0}'
2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51818
,2017-08-02 13:35:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GuZV6MUSTXVJffYmBDZZKhxn7cmek1BD","error":null,"portNumber":51818}'
,2017-08-02 13:35:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GuZV6MUSTXVJffYmBDZZKhxn7cmek1BD', error: 'null', listeningPort: '51818''
,2017-08-02 13:35:23 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:51818
[ThaliCore] Session.disconnect() peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GuZV6MUSTXVJffYmBDZZKhxn7cmek1BD","error":"Session disconnected","portNumber":null}',
,[ThaliCore] Session.deinit peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 ,13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18EAED4C-36F9-42F4-85C3-9,F97B529CE7D
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:544E1963-72AB-4976-83C3-D98BB4166601
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1E06C374-CB3C-4D19-9DBC-249F54A9464A
2017-08-02 1,3:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
[ThaliCore] Browser.startListening
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
2017-08-02 13:35:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F810FD1D-5AEA-463E-8C18-4DA0A132C00B","generation":0}'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F810FD1D-5AEA-463E-8C18-4DA0A132C00B, (syncValue: wTMl088GfmLjPUxP7hsHgsCccWWerWRv)'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A13,2C00B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
2017-08-02 13:35:27, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"03768CE9-40C2-463B-93B4-8F5364C40B1B","generation":0}'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51822
,2017-08-02 13:35:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wTMl088GfmLjPUxP7hsHgsCccWWerWRv","error":null,"portNumber":51822}'
,2017-08-02 13:35:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wTMl088GfmLjPUxP7hsHgsCccWWerWRv', error: 'null', listeningPort: '51822''
,Connecting to the localhost:51822
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:51822
[ThaliCore] Session.startOutputStream(with:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D
[ThaliCore] Advertiser: session connected Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D
,[ThaliCore] Session.startOutputStream(with:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
[ThaliCore] Advertiser: session connected Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
[ThaliCore] Session.startOutputStream(with:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-02 13:35:41 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:35:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 ,13:35:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1E06C374-CB3C-4D19-9DBC-2,49F54A9464A
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51822
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wTMl088GfmLjPUxP7hsHgsCccWWerWRv","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:AB616CAE-D6E1-4DAB-8830-7D71E9DE20E9
,[ThaliCore] Session.deinit peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3437029A-5592-425D-88F9-94BA127A2E7C
2017-08-02 1,3:35:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] Browser.startListening
2017-08-02 13:35:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"F810FD1D-5AEA-463E-8C18-4DA0A132C00B","generation":0}'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F810FD1D-5AEA-463E-8C18-4DA0A132C00B (syncValue: OEqvYTEn5MdFQDTUC1ivJokiMN6eEtC9)'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"03768CE9-40C2-463B-93B4-8F5364C40B1B","generation":0}'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
2017-08-02 13:35:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD28B5DB-E788-401E-9F57-0536CE0FD977","generation":0}'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
2017-08-02 13:35:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3","generation":0}'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,10FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,10FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F8,10FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
[ThaliCore] Advertiser: session connected Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B error: max retries exceeded
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OEqvYTEn5MdFQDTUC1ivJokiMN6eEtC9","error":"Connection could not be established","portNumber":null}'
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OEqvYTEn5MdFQDTUC1ivJokiMN6eEtC9', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:35:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD28B5DB-E788-401E-9F57-0536CE0FD977 (syncValue: f2wCrRazwVENRTE2DTnn2j3Pik1YPvYE)'
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserRelay.deinit
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] Advertiser: session connected Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] Session.startOutputStream(with:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] Session.startOutputStream(with:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [1, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] Session.startOutputStream(with:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: aw50DvIbk5dqYKQo4iTCD4l8RW4wc3PF048Hn72ues1dQChWTxsyBX7WI0jUxzVDAnX9V1rE2BZSyrJUFXwSkyMKUQX6BWUEPELSne35Bo0w3QyJorWaC6wzRYS9yd6UiP5ttz6z7W8NMBGcJCtfAIhFSAS67DhYe4R4MybfvOewINF3dZh4EZrGKx0LhCphzAElhQepGzqXJiCSWGqSgn6te7gBgXtZmJKryfnOLEGZ3KYpJFAju3OAfGPaf65IMnZLvPflh68gUKHibxdZZMspvmcydZAwOfRgacXxTcWHRxPssM3o1qBWXXLNdujjDszmeRtiCUfiyybQyyG1ZGjvq1H59v,LtH7uQqTRA0izGSN9Ehd8JpIQ0f1Wd44lSZI7tHuyuWnmGo05UnLisb2rCG6BZa3jwx0oq2ez9BvnL9ooe2wO1kqrtkgnXR15pzkCssB9C4FqdfDWnaphKCVXDaivxOVYDG972XmEzQm83XlAd9rcRPbhKNJaTMA2IGYed9vCjdmvHgPg0i1XfoeeMFK0CZezGpGJYAY2K18BdaOemS1cIpDIFeR60LL06p19ba6ltXNrWzPmcuaT0fcjvVakdYU,a1r3cK28RNUgFHESMJKawaDXaBWryCeihw4Z9AANl6VTxZWUsUDZK7vyVg6DlZ0hgVSjFcbaOrkwgoHsmdWpjxj3HQF6eFwz3DCHdlkkjtqjlI7LKMJGzLPulTXT7TJxBkjrbLUJMkDAt0kklnf9274yrKl7BulgUdeGZHGkRPFhHNAgNyyTYIxtP67I7RouGwCDsK0svQmgcoG0hgrspAXds0VeNNwzu77ELXf0OXVOxgcHs4XNMw4WzjrttLM,n,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,D,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,f,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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
[ThaliCore] Session.startOutputStream(with:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
[ThaliCore] Session.startOutputStream(with:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3
[ThaliCore] Session.startOutputStream(with:) peer:558E3B4F-2DA6-43D0-A21E-0A0,FE13666B3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 4, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (15289 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51847
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withE,rror:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: j3mzdT2WEqqhuRhP8pkrYJc6Xd4wHGTPKXtJ0JJH99RmLGLerA1E04TPeNjXtDcjoeAcpnFvZ44OOFN8zVwznO7e4h10894NP3pKj89P1j0FeR5gLh75JEkr6fVRriUiCAMeKLwrJVi2zoAxjDDhrErC01VtcCS9CPbnc0SevrNsHzTMjI,zpTJqB6tzO5Z8fDtr21K5f0dnqmWlQXIFuYcAoB9ZtocNydLUJhMhAWlWoEjg2yd99gPkMwN8gzfLC3UDzzcS8G0QcIvnkXd82iEJ5yrEFlvNtu1OiAJRSPvYRrRyfclGp2U9yS1QCymMXLOzumiawvO1gUOiotkAAi8G0p2yEqWW5BDD4oKseRpGeohLWqsUGYKszu18hikNnnYuybw5NyJyXcO0vT2EdfmGQLvTEri5ojbdu43rBLJb6vYBhre,nmCh0MraSHvklw8JEoESE9l2Ednkq0U2QvXIciGa5rEhsFW3g9Bx5Hw59icG3vfxLLpAPSDVrXkx5QGsSOGWr5W88v9XrxHCNwmcEKgxZfHDY8rww1lV2alMoNmM6IhVYNbwnsSbsOKjLl57NX84G5RJBoxJ9hrxhVrONbgVCTZatTsnqPomzeM6ApTLa4pT2lTkdypGJINYeuhvLlCayfXMz9mkWV5vC5UzLZrvzlBqpaHAFmqiBdzt1t3TpZev,5K4rp8ofrv2s8R1PpOlDC6VAz0g9ujsjExMzTTqmsTYHMPnvjJjk6xbWV9OaCUWX76glXswu1yOoLZtDtPfYNK6O7yEgol81gqwj1tpnrl1eG5XcMEmYBP78Vg6Ad7KWBWYY6Hqt0wy09RL6FzymQhyjAF9RBptr4HieWgJyeAw42DPYTEuZ8YWRYOusaVbmVbA7Gjnr8O0DNaWW2E0FxPDgD0yxgUxWvCikotmQjQzmyl1TIr2fUCkhD6wg2cRB,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,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,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 5, 6, 8, 9]
,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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 5, 6, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:35:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f2wCrRazwVENRTE2DTnn2j3Pik1YPvYE","error":null,"portNumber":51847}'
,2017-08-02 13:35:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f2wCrRazwVENRTE2DTnn2j3Pik1YPvYE', error: 'null', listeningPort: '51847''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 5, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,Connecting to the localhost:51847
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,Connecting to the localhost:51847
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,Connecting to the localhost:51847
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 5, 6, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,Connected to the localhost:51847
,Connected to the localhost:51847
,Connected to the localhost:51847
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 5, 6, 10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 5, 6, 10, 11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 5, 6, 11, 12]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 5, 6, 12]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 5, 6]
,ok 96 got the same data back
,# teardown
,2017-08-02 13:35:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3437029A-5592-425D-88F9-94BA127A2E7C
2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:AD28B5DB-E788-401E-9F57-0536CE0FD977
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51847
[ThaliCore] Session.disconnect() p,eer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:2F93769B-EFD4-42BB-BF80-0611E470C666
,# Can shift data securely
,[ThaliCore] Session.session(_:peer:didChange:) peer:558E3B4F-2DA6-43D0-A21E-0A0FE13666B3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2A2FAD16-B69B-48BB-8217-693632C78C14
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
[ThaliCore] Browser.startListening
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"AD28B5DB-E788-401E-9F57-0536CE0FD977","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD28B5DB-E788-401E-9F57-0536CE0FD977 (syncValue: 6fB3l33QzpRWERHROxJrSqylbBrNxHYS)'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6133E365-15A1-4D8C-9D13-580E318DED29","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35268274-9198-49CF-822E-A7FA7B1EE03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35268274-9198-49CF-822E-A7FA7B1EE03C", generation: 0)
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35268274-9198-49CF-822E-A7FA7B1EE03C","generation":0}'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
[ThaliCore] Advertiser: session connected Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AD28B5DB,-E788-401E-9F57-0536CE0FD977 error: max retries exceeded
2017-08-02 13:36:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6fB3l33QzpRWERHROxJrSqylbBrNxHYS","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6fB3l33QzpRWERHROxJrSqylbBrNxHYS', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:36:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6133E365-15A1-4D8C-9D13-580E318DED29 (syncValue: 28SssKr,i5wLL7xvDJsE2WYmshBQ3eOF1)'
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6133E365-15A1,-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
[ThaliCore] Session.startOutputStream(with:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 5, 6, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeS,treams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 5, 6]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51866
2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28SssKri5wLL7xvDJsE2WYmshBQ3eOF1",,"error":null,"portNumber":51866}'
2017-08-02 13:36:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '28SssKri5wLL7xvDJsE2WYmshBQ3eOF1', error: 'null', listeningPort: '51866''
,Connecting to the localhost:51866
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 5, 6, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:51866
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-08-02 13:36:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2A2FAD16-B69B-48BB-8217-693632C78C14
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6133E365-15A1-4D8C-9D13-580E318DED29
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51866
[ThaliCore] Session.disconnect() p,eer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6133E365-15A1-4D8C-9D13-580E318DED29:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
[ThaliCore] Advert,iserRelay.deinit
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"28SssKri5wLL7xvDJsE2WYmshBQ3eOF1","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A6416A01-7433-4745-962F-A44CFEAB83C5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A6416A01-7433-4745-962F-A44CFEAB83C5
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
2017-08-02 13:36:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD28B5DB-E788-401E-9F57-0536CE0FD977","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD28B5DB-E788-401E-9F57-0536CE0FD977, (syncValue: BnzveJuF3f9VRsOOMM0QQuqwVk0QEG6J)'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0,FD977", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"6133E365-15A1-4D8C-9D13-580E318DED29","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
2017-08-02 13:36:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
2017-08-02 13:36:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:A6416A01-7433-4745-962F-A44CFEAB83C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6416A01-7433-4745-962F-A44CFEAB83C5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:36:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BnzveJuF3f9VRsOOMM0QQuqwVk0QEG6J","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:36:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BnzveJuF3f9VRsOOMM0QQuqwVk0QEG6J', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:36:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:36:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3354EF96-D625-4161-8D00-E338DDA254DF (syncValue: nhP8EvEr8TsS7SBV4jPH76J,Zeoem78Yo)'
2017-08-02 13:36:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3354EF96-D625-4161-8D00-E338D,DA254DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:36:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51874
,2017-08-02 13:36:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nhP8EvEr8TsS7SBV4jPH76JZeoem78Yo","error":null,"portNumber":51874}'
,2017-08-02 13:36:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nhP8EvEr8TsS7SBV4jPH76JZeoem78Yo', error: 'null', listeningPort: '51874''
,Connecting to the localhost:51874
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,Connected to the localhost:51874
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 5, 6, 14, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,2017-08-02 13:36:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:A6416A01-7433-4745-962F-A44CFEAB83C5
2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:,36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3354EF96-D625-4161-8D00-E338DDA254DF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51874
[ThaliCore] Session.disconnect() p,eer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16DA64B2-8F6B-4510-9C75-4EBA1B17A215
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AAC7114D-9198-4417-ABCB-FAF457EC1EA7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AAC7114D-9198-4417-ABCB-FAF457EC1EA7
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
2017-08-02 13:36:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}]'
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peer,Identifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}]'
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","genera,tion":0}'
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:AAC7114D-9198-4417-ABCB-FAF457EC1EA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AAC7114D-9198-4417-ABCB-FAF457EC1EA7", generation: 0)
2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}]'
2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {",peerAvailable":false,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}'
,2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8","generation":0}]'
,2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8","generation":0}'
2017-08-02 13:36:31 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41D3B57A-35E7-466F-9DBF-DA142AC44F5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41D3B57A-35E7-466F-9DBF-DA142AC44F5C", generation: 0)
2017-08-02 13:36:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"41D3B57A-35E7-466F-9DBF-DA142AC44F5C","generation":0}]'
2017-08-02 13:36:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"41D3B57A-35E7-466F-9DBF-DA142AC44F5C","generation":0}'
2017-08-02 13:36:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:36 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AAC7114D-9198-4417-ABCB-FAF457EC1EA7
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:36 - DEBUG thaliMobileNati,veWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-08-02 13:36:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9C197985-6B35-416E-B7BF-73E25D070D4D
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpd,ateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE3053BB-E46B-4F9A-A7DA-4C6B65421BCB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AE3053BB-E46B-4F9A-A7DA-4C6B65421BCB
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AE3053BB-E46B-4F9A-A7DA-4C6B65421BCB
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:37 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-08-02 13:36:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-02 13:36:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1decb891-4687-48e2-85ee-9dc5d8e103ed error: startListeningNotActive
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"FpMCIFevc3RE2fUSJvHY64wIJalM3EHq","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:080096AE-9076-48F4-8C10-D757CF2D7C4C
[ThaliCore] Browser.startListening
2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:36:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JfHpNpZgKuctnxfeZYdctFbXfJUMkndx","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
ok 136 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
# teardown
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}]'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D7E3E79-D5D1-4786-B3B2-CE7BD877216C
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,# teardown
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}]'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:1d946949-0169-4446-bcf8-79095e8d4db8
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B1240C8D-B477-419D-98C6-0B92452098A6
2017-08-02 1,3:36:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6081F6C6-C3D1-4B64-B214-7F8CF14FB19F
[Tha,liCore] Browser.startListening
,2017-08-02 13:36:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:36:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3354EF96-D625-4161-8D00-E338DDA254DF","generation":0}'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3354EF96-D625-4161-8D00-E338DDA254DF (syncValue: qfDi41sIuiBEWEzE5hE6J0wqXwx0jSQK)'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2D5EA3C1-2612-4C80-833C-86BA8D46ADA6","generation":0}'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69DFFFC2-5186-4945-983D-DB6839F2BF34","generation":0}'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3354EF96-D625-4161-8D00-E338DDA254DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:33,54EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,354EF96-D625-4161-8D00-E338DDA254DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:36:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qfDi41sIuiBEWEzE5hE6J0wqXwx0jSQK","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:36:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qfDi41sIuiBEWEzE5hE6J0wqXwx0jSQK', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:36:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:36:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2D5EA3C1-2612-4C80-833C-86BA8D46ADA6 (syncValue: sl95sDiCahTBvzAwW46ub76,85Z0KbJcq)'
2017-08-02 13:36:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D5EA3C1-2612-4C80-833C-86BA8,D46ADA6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:36:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51884
,2017-08-02 13:36:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sl95sDiCahTBvzAwW46ub7685Z0KbJcq","error":null,"portNumber":51884}'
,2017-08-02 13:36:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sl95sDiCahTBvzAwW46ub7685Z0KbJcq', error: 'null', listeningPort: '51884''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) found active relay
,2017-08-02 13:36:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EKdFydLNlHBEVZc3NsPZ7yzPj89YXgj9","error":null,"portNumber":51884}'
,ok 144 No error
,ok 145 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
ok 146 Got null as expected
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 5, 6, 14, 15, 16]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) found active relay
,2017-08-02 13:36:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u5pTSIev7YVBc7V8mAxJvwWtazdVsFkt","error":null,"portNumber":51884}'
,ok 147 No error
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 148 Ports equal
,# teardown
,2017-08-02 13:36:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B1240C8D-B477-419D-98C6-0B92452098A6
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51884
[ThaliCore] VirtualSocket.closeStr,eams() vsID:16
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] Session.disconnect() peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3,, 5, 6, 14, 15]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-08-02 13:36:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-02 13:36:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-02 13:36:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-02 13:36:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-02 13:36:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 51887'
,ok 149 Should throw
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 51889'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 51892'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 51896'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
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
2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 51901'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 51905'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 51909'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - close'
2017-08-02 13:36:59, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 51913'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:36:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 51917'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
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
,2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'listening 51969'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'listening 51973'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-02 13:37:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 51976'
,ok 196 port must be in range
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 51977'
,ok 197 second start should return same port
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 51979'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-02 13:37:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 200 Passed bogus id
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 201 Passed good id but bogus port
2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerI,D foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 51981
,ok 207 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9326440E-49A8-4DC5-9049-885DBB40813A
[ThaliCore] Browser.startListening
2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69DFFFC2-5186-4945-983D-DB6839F2BF34","generation":0}'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 69DFFFC2-5186-4945-983D-DB6839F2BF34 (syncValue: O5OcLzbcB7FBVxdziFVJVUP7f93v1gNT)'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
2017-08-02 13:37:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C712BB72-1ECB-455C-8BB1-65EBA45DEC6A","generation":0}'
2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A952A36-869C-4BA1-B6B2-B18200FBF636","generation":0}'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4
[ThaliCore] Advertiser: session connected Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
[ThaliCore] Advertiser: session connected Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certif,icateHandler:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:69DFFFC2,-5186-4945-983D-DB6839F2BF34 error: max retries exceeded
,2017-08-02 13:37:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O5OcLzbcB7FBVxdziFVJVUP7f93v1gNT","error":"Connection could not be established","portNumber":null}'
2017-08-02 13:37:15 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'O5OcLzbcB7FBVxdziFVJVUP7f93v1gNT', error: 'Connection could not be established', listeningPort: '%s''
2017-08-02 13:37:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017,-08-02 13:37:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C712BB72-1ECB-455C-8BB1-65EBA45DEC6A (syncValue: 9CrHZTP2ujcTops11oxmu9XAe114ur1i)'
2017-08-02 13:37:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[Thali,Core] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB7,2,-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51995
2017-08-02 13:37:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9CrHZTP2ujcTops11oxmu9XAe114ur1i","error":null,"portNumber":51995}'
,2017-08-02 13:37:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9CrHZTP2ujcTops11oxmu9XAe114ur1i', error: 'null', listeningPort: '51995''
,ok 210 should be equal
,2017-08-02 13:37:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A952A36-869C-4BA1-B6B2-B18200FBF636 (syncValue: dJfSJ637OF2JPSI3geWlY64ygOntacuw)'
,2017-08-02 13:37:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51999
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dJfSJ637OF2JPSI3geWlY64ygOntacuw","error":null,"portNumber":51999}'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dJfSJ637OF2JPSI3geWlY64ygOntacuw', error: 'null', listeningPort: '51999''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51995
[ThaliCore] Session.disconnect() p,eer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:4A952A36-869C-4BA1-B6B2-B18200FBF636
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51999
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,# Multiple local http requests
,listening on 52001
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:38EB4510-C4BB-4339-8267-E8BFF2A630EC
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:37:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:37:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C712BB72-1ECB-455C-8BB1-65EBA45DEC6A","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C712BB72-1ECB-455C-8BB1-65EBA45DEC6A (syncValue: fXvfwmhb4QfzGizWEi9uHqruLe2LOAHL)'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A952A36-869C-4BA1-B6B2-B18200FBF636","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"D0A7596E-3DFD-4990-A0F0-BB946745D9EF","generation":0}'
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9,F6","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,12BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fXvfwmhb4QfzGizWEi9uHqruLe2LOAHL","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fXvfwmhb4QfzGizWEi9uHqruLe2LOAHL', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A952A36-869C-4BA1-B6B2-B18200FBF636 (syncValue: Nfg3fBlrks1FEECmlQdKwb2,xQysZG4Zl)'
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A952A36-869C-4BA1-B6B2-B1820,0FBF636:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Nfg3fBlrks1FEECmlQdKwb2xQysZG4Zl","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Nfg3fBlrks1FEECmlQdKwb2xQysZG4Zl', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A7596E-3DFD-4990-A0F0-BB946745D9EF (syncValue: BLvtbTvsBhljkbRrhBwNqNx,xZWwGYebP)'
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52018
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BLvtbTvsBhljkbRrhBwNqNxxZWwGYebP","error":null,"portNumber":52018}'
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BLvtbTvsBhljkbRrhBwNqNxxZWwGYebP', error: 'null', listeningPort: '52018''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 00DC2AB4-228C-4A26-A795-434E1581F9F6 (syncValue: RxWR4v39kMinV3EvO9q7MBsnegaONtsF)'
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274
[ThaliCore] Advertiser: session connected Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Advertiser: session connected Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274
,[ThaliCore] Session.session(_:peer:didChange:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52024
,[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: connecting -> connected
,2017-08-02 13:37:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RxWR4v39kMinV3EvO9q7MBsnegaONtsF","error":null,"portNumber":52024}'
,2017-08-02 13:37:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RxWR4v39kMinV3EvO9q7MBsnegaONtsF', error: 'null', listeningPort: '52024''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisc,onnectClients() port:52018
[ThaliCore] Session.disconnect() peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
2017-08-02 13:37:4,8, - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BLvtbTvsBhljkbRrhBwNqNxxZWwGYebP","error":"Session disconnected","portNumber":null}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] ,TCPListener.deinit
,[ThaliCore] Session.deinit peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:38EB4510-C4BB-4339-8267-E8BFF2A630EC
2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF,
,[ThaliCore] BrowserManager.disconnect peer:00DC2AB4-228C-4A26-A795-434E1581F9F6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52024
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:37:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RxWR4v39kMinV3EvO9q7MBsnegaONtsF","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:51 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-02 13:37:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'listening 52028'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A41DC88-FDFB-41B3-8028-0D72D8039516
[ThaliCore] Browser.startListening
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
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
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 52029'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3643FA9B-E031-44C5-8AA3-3511885FA6B6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3643FA9B-E031-44C5-8AA3-3511885FA6B6
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3643FA9B-E031-44C5-8AA3-3511885FA6B6", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:3643FA9B-E031-44C5-8AA3-3511885FA6B6
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3643FA9B-E031-44C5-8AA3-3511885FA6B6
,[ThaliCore] Advertiser.stopAdvertising() peerID:3643FA9B-E031-44C5-8AA3-3511885FA6B6
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
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
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 52032'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
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
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-02 13:37:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'listening 52033'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D689DEA2-AAF4-4A24-9A4B-BD74F96770FA
[ThaliCore] Browser.startListening
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BE678475-1DAA-4677-A8D8-B87CEDF7A05D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BE678475-1DAA-4677-A8D8-B87CEDF7A05D
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
ok 241 all connection succeed,
,# teardown
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BE678475-1DAA-4677-A8D8-B87CEDF7A05D
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'listening 52036'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:80A067A9-1909-453A-BDA5-7627D953A87D
[ThaliCore] Browser.st,artListening
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "41CDC3D2-0553-447D-8CE4-2416CF50E88A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:41CDC3D2-0553-447D-8CE4-2416CF50E88A
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:55 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:41CDC3D2-0553-447D-8CE4-2416CF50E88A
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'listening 52038'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5077609B-9D85-4EA3-81BC-F64B0BF1A1D0
[ThaliCore] Browser.startListening
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00F81F17-31A6-478F-B3EE-784631381E4D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:00F81F17-31A6-478F-B3EE-784631381E4D
2017-08-02 1,3:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00F81F17-31A6-478F-B3EE-784631381E4D
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-02 13:37:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-02 13:37:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-02 13:37:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-02 13:37:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-08-02 13:37:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-02 13:37:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-02 13:37:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-02 13:38:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
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
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 52041'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DFED61F-5049-4298-BB95-0F80D767F16F
[ThaliCore] Browser.st,artListening
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
,ok 269 advertisingActive matches
2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 52042'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3772F0DC-87F1-4C0B-B983-61919A8753AB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3772F0DC-87F1-4C0B-B983-61919A8753AB
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3772F0DC-87F1-4C0B-B983-61919A8753AB
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 52044'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
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
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'listening 52045'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2B708C2-C65D-4168-A6AE-C23339311718
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5054820D-90EB-4D0B-9C85-F5A7951960E1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5054820D-90EB-4D0B-9C85-F5A7951960E1
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFE11449-403B-465C-8474-A0A7BD88124B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFE11449-403B-465C-8474-A0A7BD88124B", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","generation":0}]'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5054820D-90EB-4D0B-9C85-F5A7951960E1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5054820D-90EB-4D0B-9C85-F5A7951960E1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
2017-08-02 13:38:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}]'
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5054820D-90EB-4D0B-9C85-F5A7951960E1
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-08-02 13:38:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,ok 277 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,# can still do HTTP requests between peers with coordinator
,2017-08-02 13:38:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-08-02 13:38:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'listening 52047'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:11F2F362-6C64-4861-9AB3-DD113F00BD29
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
2017-08-02 13:38:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-,4A26-A795-434E1581F9F6", generation: 0)
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
2017-08-02 13:38:0,5 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4214F04-2954-44F1-BCC5-45677AFEBDAC (syncValue: 4ZI2oQiRq4KCKpfoh0s3jmegYsPwPeqX)'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
2017-08-02 13:38:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}]'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}]'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}]'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00DC2AB4-228C-4A26-A795-434E1581F9F6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}]'
2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
,2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-02 13:38:09 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:38:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4ZI2oQiRq4KCKpfoh0s3jmegYsPwPeqX","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4ZI2oQiRq4KCKpfoh0s3jmegYsPwPeqX', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:38:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679 (syncValue: ScGK30CEqJVOTn8bggv623i,fDWAGM4pd)'
2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833,B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52053
,2017-08-02 13:38:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ScGK30CEqJVOTn8bggv623ifDWAGM4pd","error":null,"portNumber":52053}'
,2017-08-02 13:38:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ScGK30CEqJVOTn8bggv623ifDWAGM4pd', error: 'null', listeningPort: '52053''
,2017-08-02 13:38:13 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 5, 6, 14, 15, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandle,r
,2017-08-02 13:38:14 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:14 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [1, 3, 5, 6, 14, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.did,SocketDisconnectHandler
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52053
[ThaliCore] Session.disconnect() p,eer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-02 13:38:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CFE11449-403B-465C-8474-A0A7BD88124B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:38:20 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
,ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 52055'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 52056'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5CE67F6-3B41-4382-BA82-7022B07C971A
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}]'
2017-08-02 13:38:20 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}'
2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}]'
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","generation":0}'
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:38:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopp,ed state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 52057'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC292180-2A44-4059-974C-50619F3DC8AF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC292180-2A44-4059-974C-50619F3DC8AF
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 311 error should be null
,ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC292180-2A44-4059-974C-50619F3DC8AF", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC292180-2A44-4059-974C-50619F3DC8AF
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EC292180-2A44-4059-974C-50619F3DC8AF
[ThaliCore] Advertiser.stopAdvertising() peerID:EC292180-2A44-4059-974C-50619F3DC8AF
2017-08-02 13:38:21 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 52060'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-02 13:38:22 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
,ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'listening 52061'
,ok 330 first call should succeed
ok 331 first call should succeed
,ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-02 13:38:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-02 13:38:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e2488d9-ad63-49d9-a478-a4732fce16eb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e2488d9-ad63-49d9-a478-a4732fce16eb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
,ok 345 error should be null
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
,2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8c8f7a21-987d-4bf7-97a2-4047b7248743","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8c8f7a21-987d-4bf7-97a2-4047b7248743","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83cd8641-fcaf-428c-b854-026cbc36b782","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83cd8641-fcaf-428c-b854-026cbc36b782","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"18ad2248-f705-4084-beb3-281227374002","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"48a0bb2a-ef6c-4284-a719-27abe558e6c3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"18ad2248-f705-4084-beb3-281227374002","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"48a0bb2a-ef6c-4284-a719-27abe558e6c3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ac429883-d85f-4c01-8bf7-f2cc934c074b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ac429883-d85f-4c01-8bf7-f2cc934c074b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-02 13:38:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-08-02 13:38:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d8dbf24-b9b3-46a0-9adc-e293b1aad431","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 384 peer should be available
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d8dbf24-b9b3-46a0-9adc-e293b1aad431","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 385 peer should be available
,ok 386 should store correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3d8dbf24-b9b3-46a0-9adc-e293b1aad431","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'listening 52062'
2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d1444d-d704-4253-bfe9-1fb35d2e1b04","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d1444d-d704-4253-bfe9-1fb35d2e1b04","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"25d1444d-d704-4253-bfe9-1fb35d2e1b04","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'listening 52063'
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cd3c5351-ed71-4ae1-a1a8-be00747207c2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cd3c5351-ed71-4ae1-a1a8-be00747207c2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"457518f0-aad8-465c-a985-d32a636620b9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"457518f0-aad8-465c-a985-d32a636620b9","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'listening 52064'
2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"890742a5-1f7f-4fac-a9c8-a72305a86859","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33983db9-7f07-4571-ad72-5e75a1e27f91","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"33983db9-7f07-4571-ad72-5e75a1e27f91","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33983db9-7f07-4571-ad72-5e75a1e27f91","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"33983db9-7f07-4571-ad72-5e75a1e27f91","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"890742a5-1f7f-4fac-a9c8-a72305a86859","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
,ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'listening 52065'
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"27db92b2-30e7-4dd9-99a0-2cce947bed1c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"024098f2-38d1-4a49-be3a-a40ff5711112","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"27db92b2-30e7-4dd9-99a0-2cce947bed1c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"024098f2-38d1-4a49-be3a-a40ff5711112","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
,ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-08-02 13:38:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55c9dd0b-9b63-41b8-b51e-22912500f782","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55c9dd0b-9b63-41b8-b51e-22912500f782","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55c9dd0b-9b63-41b8-b51e-22912500f782","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 437 new port handled correctly
,2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55c9dd0b-9b63-41b8-b51e-22912500f782","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled, correctly
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55c9dd0b-9b63-41b8-b51e-22912500f782","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 new,AddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-08-02 13:38:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
,ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-08-02 13:38:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-08-02 13:38:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-08-02 13:38:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
,ok 461 the same hostAddress
,ok 462 the same portNumber
,# teardown
,2017-08-02 13:38:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 466 contains expected properties
ok 467 the same hos,tAddress
ok 468 the same portNumber
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 52066'
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"56b603a9-b555-4da2-9959-05b69c42c0d9","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"56b603a9-b555-4da2-9959-05b69c42c0d9","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 52067'
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4b33227b-fd43-41c1-83d2-77e8345edafc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:4b33227b-fd43-41c1-83d2-77e8345edafc
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4b33227b-fd43-41c1-83d2-77e8345edafc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-08-02 13:38:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-08-02 13:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
,ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-08-02 13:38:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
,ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-08-02 13:38:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'listening 52068'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF3FFDD3-E017-4AE9-9C61-18631851BA82
[ThaliCore] Browser.startListening
2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bef3e2e1-9aae-444c-9c2d-d521fd4e9f66","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"612f9441-7a58-454e-af0e-b387257ac12b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bef3e2e1-9aae-444c-9c2d-d521fd4e9f66","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"612f9441-7a58-454e-af0e-b387257ac12b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'listening 52069'
2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c85980e-d4e0-4100-a6f4-6528e4d2bf26","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98f3fca6-bcf8-4b58-bb1b-3f2fd108e851","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c85980e-d4e0-4100-a6f4-6528e4d2bf26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98f3fca6-bcf8-4b58-bb1b-3f2fd108e851","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-08-02 13:38:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'listening 52070'
ok 518 error should be null
ok 519 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] Browser.startListening
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}]'
2017-08-02 13:38:36 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679 (syncValue: 0)'
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
2017-08-02 13:38:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","generation":0}]'
2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","generation":0}'
,2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","generation":0}]'
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","generation":0}'
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] Advertiser: session connected Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
,[ThaliCore] Session.session(_:peer:didChange:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] Session.startOutputStream(with:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [1, 3, 5, 6, 14, 15, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B8B1B7E3,-CFBF-4090-9ADB-F4833B9D6679 error: max retries exceeded
2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8B2DDBB7-B3DF-467C-B63F-625FA51822DC (syncValue: 1)'
2017-08-02 13:38:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52082
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":52082}'
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8222BD6A-6049-42EA-8E3E-EADA99C64585 (syncValue: 2)'
,2017-08-02 13:38:50 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 5, 6, 14, 15, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:50 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:50 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] Advertiser: session connected Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C421471F-9A7D-45A4-AB76-3A9780512700 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52086
,2017-08-02 13:38:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":52086}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 5, 6, 14, 15, 18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:53 - DEBUG testUtils: 'Got response data'
2017-08-02 13:38:53 - DEBUG testUtils: 'Got end'
ok 524 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
,[ThaliCore] Session.session(_:peer:didChange:) peer:C421471F-9A7D-45A4-AB76-3A9780512700 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] Session.startOutputStream(with:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 5, 6, 14, 15, 18, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:38:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8222BD6A-6049-42EA-8E3E-EADA99C64585","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B
,2017-08-02 13:38:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-02 13:38:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:53 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
2017-08-02 13:38:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] Virt,ualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 5, 6, 14, 15, 18, 20, 21]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 5, 6, 14, 15, 20, 21]
,[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 5, 6, 14, 15, 20]
,ok 525 error should be null
,ok 526 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[Th,aliCore] VirtualSocket.deinit vsID:20 [1, 3, 5, 6, 14, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.did,SocketDisconnectHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-08-02 13:38:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,2017-08-02 13:38:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-08-02 13:38:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 clean kill
ok 541 should be equal
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
,ok 587 first enqueue is fine
,ok 588 is an agent
,ok 589 second enqueue is fine
,ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
,ok 593 good enqueue
,ok 594 Identity should match
,2017-08-02 13:39:07 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:39:07 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-08-02 13:39:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
ok 598 enqueue worked
ok 599 is an agent
ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
ok 602 start action is killed
ok 603 killed action is still killed
ok 604 enqueued action when stopped is killed
ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
ok 610 wrong arg type
,ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
,ok 618 Action was killed
ok 619 The original kill was called too
ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-08-02 13:39:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
ok 632 Start should not be called
ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-02 13:39:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 634 Got right error
ok 635 Start should not be called
ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got null
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 638 is an agent
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 664 is an agent
,ok 665 First does not throw
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-08-02 13:39:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
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
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-08-02 13:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-08-02 13:39:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-08-02 13:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-08-02 13:39:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
ok 684 correct error message
,# teardown
,2017-08-02 13:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-08-02 13:39:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
,ok 689 Start after killed
,# teardown
,2017-08-02 13:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
ok 691 must return null after successful kill
,# teardown
,2017-08-02 13:39:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-08-02 13:39:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-08-02 13:39:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-08-02 13:39:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,2017-08-02 13:39:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
ok 704 milliseconds cannot be greater than one_day
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
,2017-08-02 13:39:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
ok 720 good preAmble
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
ok 730 keys match
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
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
2017-08-02 13:39:36 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-08-02 13:39:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-08-02 13:39:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-08-02 13:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-08-02 13:39:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-08-02 13:39:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-08-02 13:39:43 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
,# teardown
,2017-08-02 13:39:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-08-02 13:39:45 - WARN thaliNotificationClient: 'peer is not available'
2017-08-02 13:39:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-08-02 13:39:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-08-02 13:39:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
ok 769 peer state should be RESOLVED
,# teardown
,2017-08-02 13:39:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-08-02 13:39:47 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-08-02 13:39:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-08-02 13:39:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-08-02 13:39:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-08-02 13:39:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-08-02 13:39:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-08-02 13:39:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-08-02 13:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-02 13:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-08-02 13:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-08-02 13:39:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
,ok 806 not equal connection type
,ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-08-02 13:39:56 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-08-02 13:39:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
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
,2017-08-02 13:39:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-08-02 13:39:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
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
,2017-08-02 13:39:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-08-02 13:39:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-08-02 13:39:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-08-02 13:39:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-08-02 13:40:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-08-02 13:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-08-02 13:40:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-08-02 13:40:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-08-02 13:40:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-08-02 13:40:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-08-02 13:40:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-08-02 13:40:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:10 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-08-02 13:40:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-08-02 13:40:13 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-08-02 13:40:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-08-02 13:40:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-08-02 13:40:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-08-02 13:40:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-02 13:40:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
,# teardown
,2017-08-02 13:40:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-08-02 13:40:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
,ok 863 same localDbName
,ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-08-02 13:40:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'listening 52217'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] Browser.startListening
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2D5A4CED-5489-48C5-AAA0-5C484A196223
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
2017-08-02 13:40:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","generation":0}]'
2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DBD8E41B-2745-45AA-9AFC-91E8212BCF42 (syncValue: 3)'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}]'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52220
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":52220}'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 4)'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 5, 6, 14, 15, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 5, 6, 14, 15]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 3, 5, 6, 14, 15, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:27 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 5, 6, 14, 15, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Advertiser: session connected Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Advertiser: session connected Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 5, 6, 14, 15, 23, 24, 25]
,[ThaliCore] Session.session(_:peer:didChange:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0 state: notConnected -> connecting
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 5, 6, 14, 15, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 5, 6, 14, 15, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 5, 6, 14, 15, 23, 24, 25, 27]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 5, 6, 14, 15, 23, 24, 25, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 5, 6, 14, 15, 23, 24, 25, 27]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 5, 6, 14, 15, 23, 24, 25, 27, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 5, 6, 14, 15, 23, 24, 25, 29]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 5, 6, 14, 15, 23, 24, 25, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,2017-08-02 13:40:29 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:peer:didChange:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52233
,2017-08-02 13:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":52233}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 34]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 42, 43]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 5, 6, 14, 15, 23, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 5, 6, 14, 15, 24, 25, 30, 32, 35, 36, 37, 38, 39, 40, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 5, 6, 14, 15, 24, 30, 32, 35, 36, 37, 38, 39, 40, 42, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 5, 6, 14, 15, 24, 32, 35, 36, 37, 38, 39, 40, 42, 43, 44]
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 5, 6, 14, 15, 24, 32, 35, 36, 37, 38, 39, 40, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 5, 6, 14, 15, 24, 32, 35, 36, 37, 38, 39, 40, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 5, 6, 14, 15, 24, 32, 35, 36, 37, 38, 39, 40, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 5, 6, 14, 15, 24, 32, 35, 36, 37, 38, 39, 40, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 5, 6, 14, 15, 24, 35, 36, 37, 38, 39, 40, 43, 44, 45, 46, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 5, 6, 14, 15, 24, 35, 37, 38, 39, 40, 43, 44, 45, 46, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 5, 6, 14, 15, 24, 35, 37, 39, 40, 43, 44, 45, 46, 47]
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 5, 6, 14, 15, 24, 35, 37, 39, 40, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 5, 6, 14, 15, 24, 35, 37, 39, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 5, 6, 14, 15, 24, 37, 39, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [1, 3, 5, 6, 14, 15, 24, 39, 44, 45, 46, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 5, 6, 14, 15, 24, 44, 45, 46, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 5, 6, 14, 15, 24, 45, 46, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 5, 6, 14, 15, 24, 45, 47]
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 5, 6, 14, 15, 24, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 5, 6, 14, 15, 24]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2D5A4CED-5489-48C5-AAA0-5C484A196223
,2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 865 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'listening 52251'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Browser.startListening
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:26AD2EE6-305B-44CC-A33E-0510D7802E5F
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,8 [1, 3, 5, 6, 14, 15, 24, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] AdvertiserRelay.didClos,eVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 5, 6, 14, 15, 24]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
2017-08-02 13:40:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}]'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 5)'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":52233}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Session.startOutputStream(with:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [1, 3, 5, 6, 14, 15, 24, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","generation":0}]'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","generation":0}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29 (syncValue: 6)'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7FE4C83-AA88-4B5F,-8AFC-024A3E3E0A29", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:,notConnected:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 5, 6, 14, 15, 24]
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","generation":0}]'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 5, 6, 14, 15, 24, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 5, 6, 14, 15, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-02 13:40:35 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] Session.deinit peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Advertiser: session connected Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D5A64512-996D-4760-894C-603F43EE5BA7 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:E7FE4C83-AA88-4,B5F-8AFC-024A3E3E0A29:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnect,ions(on:connectionAccepted:completion:) port:0 localport:52257
2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":52257}'
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5891A3EE-D937-4353-ACE3-CA5B2BF22CDE (syncValue: 7)'
2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Advertiser: session connected Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 5, 6, 14, 15, 24, 51]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHa,ndler
,[ThaliCore] Session.session(_:peer:didChange:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 5, 6, 14, 15, 24, 51, 52]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 5, 6, 14, 15, 24, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:40:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
2017-08-02 13:40:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 866 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 5, 6, 14, 15, 24]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5A64512-996D-4760-894C-603F43EE5BA7 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52262
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":52262}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11 state: connecting -> connected
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 8)'
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":52233}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 5, 6, 14, 15, 24, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Session.startOutputStream(with:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 5, 6, 14, 15, 24, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 5, 6, 14, 15, 24, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Session.startOutputStream(with:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 3, 5, 6, 14, 15, 24, 53, 54, 55, 56]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
,[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 5, 6, 14, 15, 24, 53, 54, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-02 13:40:41 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Session.startOutputStream(with:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,7 [1, 3, 5, 6, 14, 15, 24, 53, 54, 56, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 5, 6, 14, 15, 24, 54, 56, 57]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 5, 6, 14, 15, 24, 54, 56, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Session.startOutputStream(with:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 5, 6, 14, 15, 24, 54, 56, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 5, 6, 14, 15, 24, 54, 56, 58, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B62FD9DD-B264-4CBF-8735-F2F333E048E2 (syncValue: 9)'
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0) found active relay
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":52233}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,2017-08-02 13:40:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-02 13:40:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 867 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 5, 6, 14, 15, 24, 54, 56, 59]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [1, 3, 5, 6, 14, 15, 24, 54, 56, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 5, 6, 14, 15, 24, 54, 56, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 5, 6, 14, 15, 24, 54, 56]
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:26AD2EE6-305B-44CC-A33E-0510D7802E5F
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B62FD9DD-B264-4CBF-8735-F2F333E048E2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5891A3EE-D937-4353-ACE3-CA5B2BF22CDE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-02 13:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:40:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 868 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 869 should throw
,ok 870 should throw
,ok 871 (unnamed assert)
,ok 872 (unnamed assert)
,ok 873 (unnamed assert)
,ok 874 (unnamed assert)
,ok 875 (unnamed assert)
,# teardown
,# setup
,# Call start twice and get error
,ok 876 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 877 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 878 should be equal
,# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 879 should be equal
ok 880 should be equal
ok 881 should throw
,# teardown
,# setup
,# Test TransientState
,ok 882 should throw
,ok 883 should throw
,ok 884 should be equal
,ok 885 should be equal
,ok 886 should be equal
,ok 887 should be equal
,ok 888 (unnamed assert)
,ok 889 (unnamed assert)
,# teardown
,# setup
,# No peers and empty database
,ok 890 verify failed
,ok 891 constructor called once
,ok 892 constructor called with right args
,ok 893 match start arg
,ok 894 start called once
,ok 895 stop called once
,ok 896 stop after start
,# teardown
,# setup
,# One peer and empty DB
,2017-08-02 13:40:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 897 verify failed
,ok 898 constructor called once
,ok 899 constructor called with right args
,ok 900 match start arg
,ok 901 start called once
,ok 902 stop called once
,ok 903 stop after start
,# teardown
,# setup
,# One peer with _Local set behind current seq
,2017-08-02 13:40:47 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 904 verify failed
,ok 905 constructor called once
,ok 906 constructor called with right args
,ok 907 match start arg
,ok 908 start called once
,ok 909 stop called once
,ok 910 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-08-02 13:40:48 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 911 verify failed
,ok 912 constructor called once
,ok 913 constructor called with right args
,ok 914 match start arg
,ok 915 start called once
,ok 916 stop called once
,ok 917 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-08-02 13:40:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 918 verify failed
,ok 919 constructor called once
,ok 920 constructor called with right args
,ok 921 match start arg
,ok 922 start called once
,ok 923 stop called once
,ok 924 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-08-02 13:40:49 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 925 verify failed
,ok 926 constructor called once
,ok 927 constructor called with right args
,ok 928 match start arg
,ok 929 start called once
,ok 930 stop called once
,ok 931 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 932 verify failed
,ok 933 constructor called once
,ok 934 constructor called with right args
,ok 935 match start arg
,ok 936 start called once
,ok 937 stop called once
,ok 938 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:50 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 939 verify failed
,ok 940 constructor called once
,ok 941 constructor called with right args
,ok 942 last start before stop
,ok 943 empty first start
,ok 944 full second start
,ok 945 only 2 timers
,# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-08-02 13:40:51 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 946 verify failed
,ok 947 constructor called once
,ok 948 constructor called with right args
,ok 949 start before stop
,ok 950 We got at least 3 calls to start
,ok 951 at least 3
,ok 952 default 1
,ok 953 1 run
,ok 954 default 2
,ok 955 2 run
,ok 956 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 957 start out null
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 958 back to null
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 959 still null
,ok 960 verify failed
,ok 961 constructor called once
,ok 962 constructor called with right args
,ok 963 first start before first stop
,ok 964 first stop before second start
,ok 965 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-08-02 13:40:52 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 966 verify failed
,ok 967 constructor called once
,ok 968 constructor called with right args
,ok 969 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-08-02 13:40:53 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 970 verify failed
ok 971 constructor called once
,ok 972 constructor called with right args
,ok 973 (unnamed assert)
,ok 974 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-08-02 13:40:53 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 975 verify failed
,ok 976 constructor called once
,ok 977 constructor called with right args
,ok 978 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-08-02 13:40:54 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
,ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 983 should be equal
,ok 984 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-08-02 13:40:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:40:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 985 Got right error
,# teardown
,2017-08-02 13:40:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-08-02 13:40:56 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 986 Got socket hang up
,# teardown
,2017-08-02 13:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-08-02 13:40:56 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 987 Got 500 as expected
,# teardown
,2017-08-02 13:40:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 988 should be equal
,ok 989 revs are equal
,# teardown
,2017-08-02 13:40:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-08-02 13:40:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 992 should be equal
,ok 993 revs are equal
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,# teardown
,2017-08-02 13:41:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,75A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/175A5720-,B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-08-02 13:41:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 998 Our rev is old so we should fail
,# teardown
,2017-08-02 13:41:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 999 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/175A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/1,75A5720-B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/175A5720-,B703-44D7-BDB6-9BE9EF59E16F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-08-02 13:41:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-08-02 13:41:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1000 stop caused us to fail
,ok 1001 We specifically failed on a stop before put
,# teardown
,2017-08-02 13:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1002 failed due to stop
,ok 1003 failed due to stop
,# teardown
,2017-08-02 13:41:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1004 should be equal
,# teardown
,2017-08-02 13:41:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-08-02 13:41:08 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1005 Expected bad seq error
,# teardown
,2017-08-02 13:41:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1006 Different promises
,ok 1007 Timer was cancelled
,ok 1008 should be equal
,# teardown
,2017-08-02 13:41:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1009 One go and one blocked
,ok 1010 All blocked
,ok 1011 Still blocked
,ok 1012 should be equal
,# teardown
,2017-08-02 13:41:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1013 We waited long enough
,ok 1014 should be equal
,# teardown
,2017-08-02 13:41:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1015 Should have gotten same timer promise
,ok 1016 Still same timer promise
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-08-02 13:41:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-08-02 13:41:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1019 expressPouchDB was called once
,ok 1020 expressPouchDB was called with 2 arguments
,ok 1021 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1022 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1023 PouchDB was called once
,ok 1024 PouchDB was called with 1 arguments
,ok 1025 PouchDB was called with 'dbName' as 1-st argument
,ok 1026 ThaliSendNotificationBasedOnReplication was called once
,ok 1027 ThaliSendNotificationBasedOnReplication was called with 4 arguments
,ok 1028 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
,ok 1029 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
,ok 1030 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
,ok 1031 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
,ok 1032 ThaliPullReplicationFromNotification was called once
,ok 1033 ThaliPullReplicationFromNotification was called with 4 arguments
,ok 1034 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
,ok 1035 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
,ok 1036 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
,ok 1037 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
,ok 1038 Salti was called once
,ok 1039 Salti was called with 4 arguments
,ok 1040 Salti was called with 'dbName' as 1-st argument
,ok 1041 Salti was called with 'acl' as 2-st argument
,ok 1042 Salti was called with 'thaliIdCallback' as 3-st argument
,ok 1043 Salti was called with 'options' as 4-st argument
,2017-08-02 13:41:20 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'listening 52340'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:746E813D-6FBC-4875-AE4D-1F86ED48C5A7
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CC58CE6E-B44C-4486-99F6-68D634344F44", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CC58CE6E-B44C-4486-99F6-68D634344F44
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:20 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1044 ThaliMobile.start was called once
,ok 1045 ThaliMobile.start was called with 3 arguments
,ok 1046 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1047 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1048 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1049 ThaliMobile.startListeningForAdvertisements was called once
,ok 1050 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1051 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1052 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1053 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1054 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1055 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1056 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1057 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1058 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-08-02 13:41:20 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CC58CE6E-B44C-4486-99F6-68D634344F44
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:41:20 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:41:20 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
,ok 1059 ThaliMobile.stop was called once
,ok 1060 ThaliMobile.stop was called with 0 arguments
,ok 1061 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1062 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1063 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1064 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1065 expressPouchDB was called once
,ok 1066 expressPouchDB was called with 2 arguments
,ok 1067 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1068 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1069 PouchDB was called once
,ok 1070 PouchDB was called with 1 arguments
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
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 52342'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1EBB170-797A-4C3B-BF2D-EA687523F0A6
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4E0598E8-D385-4717-961D-D62A8AD5FA08", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4E0598E8-D385-4717-961D-D62A8AD5FA08
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4E0598E8-D385-4717-961D-D62A8AD5FA08
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1105 ThaliMobile.stop was called once
,ok 1106 ThaliMobile.stop was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1108 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1109 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1110 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 52344'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E294BC1D-1C44-4E7B-B563-E7799D94E1A4
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD17FA61-D78F-4976-B672-7FDDF877B8DF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DD17FA61-D78F-4976-B672-7FDDF877B8DF
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD17FA61-D78F-4976-B672-7FDDF877B8DF
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
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 52346'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:71CAA4F1-E07F-43CF-8ED3-17C905677813
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E67C664A-B2C0-4ECD-B728-51F54C9ACE5C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E67C664A-B2C0-4ECD-B728-51F54C9ACE5C
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E67C664A-B2C0-4ECD-B728-51F54C9ACE5C
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
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 52348'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15FE004F-85C3-48BA-9DE7-EF0F7D5A2A2F
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E4691684-7EC4-4EC3-BFF4-D4D49D62B29C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E4691684-7EC4-4EC3-BFF4-D4D49D62B29C
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1111 ThaliMobile.start was called once
,ok 1112 ThaliMobile.start was called with 3 arguments
,ok 1113 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1114 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1115 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1116 ThaliMobile.startListeningForAdvertisements was called once
,ok 1117 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1118 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1119 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1120 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1121 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1122 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1123 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1124 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1125 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E4691684-7EC4-4EC3-BFF4-D4D49D62B29C
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
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
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
2017-08-02 13:41:23 - INFO Coo,rdinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_,LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
2017-08-02 13:41,:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdv,e,rtisements many times'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - sh,ould be able to call #stopAdvertisingAndListening many times'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result:, passed - error returned with bad router'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Serve,rs Manager should be null when we call start on iOS'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped, ,- make sure terminateConnection is properly hooked up'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
2017-08-02 13:41:23 - INFO CoordinatedClient: '**,*TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
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
2017-08-02 13:41:24 - DEBUG CoordinatedClient: 'test client succeed'
2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: 'all tests succeed'
,2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
