#### Test 113351851dc08641_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/94C4F50F-7021-46A0-98A4-F98805C9E68F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/94C4F50F-7021-46A0-98A4-F98805C9E68F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49612"
,(lldb)     command script import "/tmp/94C4F50F-7021-46A0-98A4-F98805C9E68F/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:49:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "411D9267-EDCD-4D54-870A-3B9232C458EB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:411D9267-EDCD-4D54-870A-3B9232C458EB
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisement,s
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F097755-644B-40E4-9A75-4A210B5E3103
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCor,e] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:097871B1-DE7F-4CCD-991F-8225D9D5F037
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onP,ort:errorHandler:) Peer(uuid: "BDF762D7-F91E-4DBB-B92D-794129695D36", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BDF762D7-F91E-4DBB-B92D-794129695D36
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BDF762D7-F91E-4DBB-B92D-794129695D36:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BDF762D7-F91E-4DBB-B92D-794129695D36", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-24 06:49:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.566663920879364
,2017-07-24 06:49:25 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-24 06:49:25 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BDF762D7-F91E-4DBB-B92D-794129695D36:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BDF762D7-F91E-4DBB-B92D-794129695D36", generation: 0)
,2017-07-24 06:49:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 06:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 06:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 06:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 06:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 06:49:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 06:49:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 06:49:32 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 06:49:32 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 06:49:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-24 06:49:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-24 06:49:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
2017-07-24 06:49:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are, out of the checkpoints plugin delay interval''
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
,2017-07-24 06:49:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-24 06:49:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-24 06:49:53 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-24 06:50:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 06:50:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1215BBF-9F77-418A-AB16-2C60B6E42FB5
[ThaliCore] Browser.startListening
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:457F9073-ECA6-4AA2-BC8F-46FCCBBB43BE
[ThaliCore] Browser.startListening
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A48D614-D772-49F4-8C3E-9440ED48D201", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4A48D614-D772-49F4-8C3E-9440ED48D201
2017-07-24 0,6:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4A48D614-D772-49F4-8C3E-9440ED48D201
2017-07-24 06:50:04 - DEBUG tha,l,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "47FEE9E3-963B-4818-A110-3BB93C87FD25", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:47FEE9E3-963B-4818-A110-3BB93C87FD25
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "47FEE9E3-963B-4818-A110-3BB93C87FD25", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:47FEE9E3-963B-4818-A110-3BB93C87FD25
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingS,t,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:47FEE9E3-963B-4818-A110-3BB93C87FD25
[ThaliCore] Advertiser.stopAdvertising() peerID:47FEE9E3-963B-4818-A110-3BB93C87FD25,
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6DE7F97-0298-41CE-BD58-FA0D64D8238F
,[ThaliCore] Browser.startListening
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6A12CD7D-7950-4B6B-B5CF-8B3408D52793:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6A12CD7D-7950-4B6B-B5CF-8B3408D52793", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ADB8CA58-4E4A-,49E1-9E9D-9EF17B37AB2E
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to nativ,e'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC
2017-07-24 0,6:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A764879-3CA2-4857-9907-8F7C5858454B
[Thal,i,Core] Browser.startListening
2017-07-24 06:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:50:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
2017-07-24 06:50:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","generation":0}'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4AD769C-CE08-4F9C-9F77-256A14CEDA92, (syncValue: ycOpMfy9TTCoZA8w9aEF7sKbSuqdffaM)'
,2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
,2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","generation":0}'
,2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60525
,2017-07-24 06:50:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ycOpMfy9TTCoZA8w9aEF7sKbSuqdffaM","error":null,"portNumber":60525}'
,2017-07-24 06:50:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ycOpMfy9TTCoZA8w9aEF7sKbSuqdffaM', error: 'null', listeningPort: '60525''
,2017-07-24 06:50:21 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-24 06:50:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC
2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60525
[ThaliCore] Session.disconnect() p,eer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F
[ThaliCore] Browser.startListe,ning
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
2017-07-24 06:50:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4AD769C-CE08-4F9C-9F77-256A14CEDA92, (syncValue: MiWNf3h6W7uFJAdAbECbEj8pn6l981f1)'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14C,EDA92", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"A8B1D4F7-116E-489E-90A9-6E13E0070383","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A,44","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
2017-07,-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83026883-B6BD-420E-91E3-BE6D772339D8","generation":0}'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MiWNf3h6W7uFJAdAbECbEj8pn6l981f1","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MiWNf3h6W7uFJAdAbECbEj8pn6l981f1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 281373AD-3A04-4E63-8025-EA0CD6FB0A44 (syncValue: BUerzgGv8rApknhAw83ma5Tne3cWg8n3)'
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:50:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60530
,2017-07-24 06:50:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BUerzgGv8rApknhAw83ma5Tne3cWg8n3","error":null,"portNumber":60530}'
,2017-07-24 06:50:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BUerzgGv8rApknhAw83ma5Tne3cWg8n3', error: 'null', listeningPort: '60530''
,Connecting to the localhost:60530
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,Connected to the localhost:60530
,2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:283211BA-FD1D-4342-BFAF-C3135477885A
[ThaliCore] Advertiser: session connected Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:283211BA-FD1D-4342-BFAF-C3135477885A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:283211BA-FD1D-4342-BFAF-C3135477885A
,[ThaliCore] Session.session(_:peer:didChange:) peer:283211BA-FD1D-4342-BFAF-C3135477885A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:283211BA-FD1D-4342-BFAF-C3135477885A
[ThaliCore] Session.startOutputStream(with:) peer:283211BA-FD1D-4342-BFAF-C3135477885A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:50:42 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 06:50:42 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-24 06:50:42 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-24 06:50:42 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2,
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
2017-07-24 06:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60530
[ThaliCore] Session.disconnect() p,eer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:283211BA-FD1D-4342-BFAF-C3135477885A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:283211BA-FD1D-4342-BFAF-C3135477885A
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BUerzgGv8rApknhAw83ma5Tne3cWg8n3","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] Session.deinit peer:283211BA-FD1D-4342-BFAF-C3135477885A
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] Browser.startListening
,2017-07-24 06:50:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:50:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","generation":0}'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 281373AD-3A04-4E63-8025-EA0CD6FB0A44 (syncValue: wJDgHyTEoULWshsHXXNQZ0ehT8ZLcGda)'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","generation":0}'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:28,1373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,81373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:28,1373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,81373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wJDgHyTEoULWshsHXXNQZ0ehT8ZLcGda","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wJDgHyTEoULWshsHXXNQZ0ehT8ZLcGda', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"281373AD-3A04-4E63-8025-EA0CD6FB0A44","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7DC295B6-5886-44D5-B750-7B97D55E9F06 (syncValue: ycH7lv83Vng7z1DsgsU1orwXyOilt5Sa)'
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
[ThaliCore] Advertiser: session connected Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60543
2017-07-24 06:50:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ycH7lv83Vng7z1DsgsU1orwXyOilt5Sa","error":null,"portNumber":60543}'
,2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ycH7lv83Vng7z1DsgsU1orwXyOilt5Sa', error: 'null', listeningPort: '60543''
Connecting to the localhost:60543
,Connecting to the localhost:60543
Connecting to the localhost:60543
,Connected to the localhost:60543
Connected to the localhost:60543
Connected to the localhost:60543
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
[ThaliCore] Session.startOutputStream(with:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
[ThaliCore] Session.startOutputStream(with:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] Session.startOutputStream(with:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 91 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5, 6, 7, 8]
ok 94 got the same data back
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received all data: BKzHRWUkKawnXqXmegwhpgoANeDkWHIe9Ydiq78QeHtVi7E1dgPuyeI9Z9zU2qfhlPZenqRNvLcqOukhOyDybnkNCFuniCfMd7C6FIyIP2OwULfXaf3U2vdhfbKlMwbIBvXWAFS2IKHcZ09l1ozDJRIcypFvGg0UDvXeSjG9yI4z7J2fG1,y88terdREcyIQ6RgTi5PWVFpHzuuP1TKGKMBwxB2aP5eTLDKuRlQudPcOMr8BCOeuJmbdUKQNXgilhCzAXUKTntURZ0TFz87TiofZEV7OVrf6r19y9logBl5HSPnwb0ZuvmqdbAkTXN22Aevu43gCQxbuGArCqKxB6WEnMSXaC0G6BFn0VeycIjZEIxOl69WpdVV0tR9GBGbWL58i8Dm1rJs2ZgueARHUnNTO10VYxs3Y7W5poOno5032Kuf1OKm,ZVlfZOVxO263xNwUggRU5Xx9BQoDmqtrFj1WGQsQm4QcqYdf413HdoYtdZm4PGuSTZ3BFOm3cDcNPB3SMTqdTKBvpcIZ6nbJnnxVieEgLOmoJAaVIUh9BQa2Y9SbngZbBbYWeNk6C52V6SQ92fjSjUQUvdvNXac42X1b3RiW51J27VfMazlApO7kmQnpkCWYYa8XB5E42ItQJboIZtUyMKMi4D2rzu2EBIWMzoln0IJXerkA4GqsY2VatUSR6U9I,WGH2JYHIpAzUN2wBKEGto7leXVBy7xt9s8WCTj2XVjOuZn9EbBIItAs34DZsExGdIApGFEepxlyINlMV6pJ2gEUGYUhn2qvMPaONUkLSEAtEbL1qr2t2WuEVP5WI8pKhDT6ZEIdlAMIEVrWeZjP7eKbHPiJ0sY4WgvZx6j2td7U1rlS9OZGcUjaT3Wboljz288gDVX2XRUP3sAFmEEWI6u8o1v27LjOWBzfTmZfA2EYHpGOHOUpqIUXseHswg5vS,lE7x8rsgifWpnberHSiXWQjZzRbjnE2efTc7BbIAhgqNCZxso0cS3PQSQcgFrZ0WM5Vs0zqixjYGunImiMzuW6oXmjyHSyBGd6GBjc2uj1SIyLjTEHw3yuPLyayHm1cWFDu3G5plUZjEl2XqSi5lG6GH1haVXxgljGLmT4OeYERkMZsEE0IH639qfmxcC01eHSECYnfoeLxjXuy9U3uxVZkZpcfyX56uibDOwEx5HjiPMFyidU47P71JI93IUdqZ,LK1sGNXsbojVXpOQdeDts0680cEBMGbKpnvLsuW1GpmMUs1hLrz04g8iGkUR6cauXmJxfjDGgFnH34mxPucCaZg6F7xw49nBgDtd2TgNtnfQrQ7FWdWmfNYavB13n6mrQTatCjPICoQANCZGqHZGDy4wpRKZJsHS8sdUQg3JMlv8OX5LXSwSG8vb5uJLha9G4atAwV3znFcwiScNeYI4nVfoIjCJDtKyHxSaffqBjziVkrBsbBsjGqFGGgHdy03x,g7BAakq1M6dnTH6VjCgvclhkxNIR7KMCqQ38VnRhaz9STJT4z70DFusHWmHriMt7u1QlVpsuMfPQRlQO7emwAEvP53YXcDAIxQRLnl9qFVOy4iJyThXUPvwJNVn6ipjLyNAeKdpYU05eMkbz4Xk6rcfNhaTDcttxt4o6MJMpCXjbFwVGoUc7PoJMS2P91EV5NS9jsRsIFL7KQFt7nJseRuRFYdUo3MeN0d9talJ0P0xWuhD8re8SjsMRTcLIA6cX,me57BImy0CrHtmw4Cr6B08eaeOZadJzw5E8HZ4foIpGui8E5Puc7rd2RmnolcNrST9G32g5hAS14iD83YC0239b3J8hBJ1Rziq4xnbYzZlClidkl2OG1duXA0qg0uiZGUoGUDmSs1BtAu54AerIlDQTPc3PJgxSVlrXm6XGMFOXAkTdZMWBFcp5sYX7x34PkO6GjV7CsWC6belNYnfroWwDdMpJec34fYjGzRmQYZLM32XZ2yjZUaDFHOFVneEqv,C3lekhyS6pkzbDQ17swXiBZBnKrMrMRsha9FMpapPcpd08Say6bKnyYPLwDdcMadKyGBVHNdetsGle7pnF2SDRkh8mCxdEVsV8JuJxJpaSrdDTJY3f0LZG1niRFq0KNAHe4wqeXpO85xBBnuxztgy6V6hByWO9NFuWYvmhoG7F2yW2dlhvfa9bUEprcfQ9xc1mXDDISMWb5KaypKQZfSKsA7xSs8DFX2IgK1FrC4XY1OI87RJWg6xOQ8nNTrCqL9,dyfPygy9b1KLnr6pdTOvreRizDfISded6pFXRz0B2DRe3SU2u6nL5heGOOdDhlTwLyvdoz89pnMBwDalgsjiahoZFWrUa4Sc6vOxMb8WqGEx9Oz0kWfbvHUydbCCERZP8gFLY6HrtyJFjEa2pLv9yRkUXgtTsiocxAgQZ8juRFylHh8wNOjEp9ZZanx5OIo2XBUjEuFsaFSdAMQhw3q2nyBAC8YV7BdXmO0CGlGf4Qs29qRU6b4yrXVUh7bVfSiA,u5yP4QsszELqB6Vkz51TBaprAQH7sl7EVFTjFA8MmvTbEG4NhwFSMXFh4WfoFLi93T5M0RWgsCFG5YFjGBwD80go8dxpbqcwprBSQ6OdM6rxydw9yWbpMn6Sc3kih2VVAXC9XPhhPNRHU29McumImvQCFbCLxGuKb2kqqQODvvOwKThmfEnAgIkYLuYzgfTp8DwaX5TQzYJ8hScqLykJCirfDPyKQyhvQ0aBye6gtnS2Np4x0hz3De00WgegyunO,n9IZbIdJq9upYRIArmA3px0dGjQAK4xksw1MfHX7Kxz9quLRyLX5QaCgC7sJQk1zvbI9VsbdGvl0C11DASQQSer86SdOExIMbQVtvwrBuewBVIeCIQmrOFOr69nxaUcalOrdDp4T2K5zkmHYWlGUUaYbNYHaNmkXNIsKxUB82pftpn0D4tZachSghBOk6RBCc9SIazV29CkAUqrYWSnOmbUsTMswFPZy3L6eaLnMgHOU48xJ0nJM6eRkpv9dr8ik,hJZjvh3xLMBGuBsM40DSyZW4iKgTbeXFYpmb5H8hmE58ryqNXkt4aucypuBpnxWf7D9XUGyqvqmMwrgUcrdhLjc0RIke44wQPzyVTRdj3frmovxtua6x9Hg6kjrfAafGd388mCNsHGUtImw8XyOTUR8xMHOQmxK3DVxjuKI0KCGcrxRUBaxlxhvP6DK1A9mJRopwwHGJT4KBmHZZVMZEdqR0oTsiF5cC8VZl9oxI2xL6fIcpKpJRACVAmEgBUbDA,DZFy14Q8pADrGOxaYka0VEdkif5RdEYKuDHHfOsD2TZknWGJJHtcovx1AQf8awClqQVj4hEuqOVL3vO9iTapKCzcoqPfy61MJkZHX8RXv61Dil7wfseeIGiGij7W631wxWH8b9NbaPBtMXqxqvidticHwxEvABHBWLgw2yl1hR3Kfg68UmU7VygAihqfqkM23uU4ieHbOVOBpqXuDrrgra2zJWigVMMbclAdKIwwYqG6IrboYwsjPT3KApnp4loK,F7lHNUFadQK3rh8aJc1gGHzF1Vh5s5w0oNrVfFVP58yM0UuD1atNNVwU5KSKlLOrNLV41BqhlI24LYrIAcPpAJAiuiyksGXi5OjdPU9EcIeNBcsm4K0Y6AO1ZMjdzxHKN4DebYPe9Qq52Jws10I4sIoKJ5FeHa6OMfbyCwop11Bjv331CQnmqzy80acyNYXb39fcZlzKZka8rIrgnTVwaCLHlVUetdyPWwkqkiQoc7QrfqQ8SLfDkZUq6ZhvRxdk,ntoblxkvIMHwB4aJ5ReN3foU6UWhVRxXfxHHwGoYY22qc0Jb0o1yuKV00jQdgGCdB9RJJ74dKGRAPcpJF7bTPm0L4gBOOVNhSBxX6Jdu4sI3mmjX34GiuCHaToXr05igmhCYU5elIJaP4vzALGrGjybMDlVmF1So1gV1sZXPDj83YqcJWWkYMC1ivSn1MdTYN98jBdJ6J080vemaKqBWxR4qj0ezMQ7jMuilKIOryy6b9JDOUUrVQ4xXRESHe4mz,f1QJHSXEdn5TZdrGnuPcEpfJwYL5RghgRQAjJD6ACB7DNKXFRbjqjj3YWZ3ONCqmmZuReq9sAjoEuD3dO08NT1QWpD77sD3sHJKfRa5jUvyW7WCMxg9kDuMXNGpGrQOZQmwJulKcXHz1GencLoCvQodIcnI4dWiS7TSbzzHZkTQg5ejWihsT1jxM7Crhb1Jq2Scd7ehDLU8DFrbs7Cyw4TEllbuI1COw8W71V7sWpg7b40s333u8kJmBwvjhzRiL,AJR8I9IHQYfDLJt1vRgQyBRseCv9xdrSODumSbA0jybun3nUer9n11MWjAj79h0uRqovbFCI7BKuJysCeKcmaN2dqOCdNENJAqmhLFbqmT4dd0QW9XzUcrB0JROB3m37AuYK3xc6aAh1hrTBJ7HQv8OFY7tIhXABCoInxVzXxUXaQIkReMGZcCygQBtyl3PY6Xi6GiplLerzs54rI6rC0xAFFZdiqM7E6zAoumCMKWZM6cz2LyWciami8pQnV6k8,izfvwTTdF2QQ3uoIwRTrU9C8N4FaS6yKWx0ThaatSYGh4xeDSHtyIi1fhSqrZaibsJnIluQgEB83UyPOgTjXNH0wyYlAIPZH5l9sdK5qCLhGggahUJYv1YN0hjFGy8EDynuqJrXBYCNTy9ptu27hBhMQZUt5hVAOqnI5KiVGYJbWuD9hSPDV3g5720nlfQKkNrxruPpv94Rp1pxH0TayDlMY4wpqCYYMlJJJzKDkPGsOi8gu6RLLx4jT8hzUAikO,yBW8RuVYufHNTtAb4cv4W4NcvW8mVXoUsXOsOjSnnIel7wjaKnSSv6i0UuffmBqQ3ZE2FdUqh3p9hIrb1JvnOKqDwzVaYQSxHP4REvO6bKtIkgIl3Qwd1qHA7YPDb1Xvq1UxfRQPLQ5UlXT2eG1McRrQK2ABvkJR1fS98DM0Jy8BELKZUDq5TsB7T8Kqsp5YFlrOCaFy52Kw9f9J4rL7zMxCpB0qdBXQ7NFjbMyhQuFI8rnwF21HD88ucflEAu8O,GQyGakYsPcNggQvRnYxjBCew037Yj8i9k30WyVvjdagdjlwh3SC4xpxMiK3IrYG3cjruC7vkiQTgHSu5RNSKPYS4IsbuGiOgEonrBzRMTvXzLfSr4SlehkpAHPUJLu0BL3vf76dzadIJ0LUw4l8yaOmtmoVyQ4Ce0YyxIG9mieQuPCL8CtSZMYriiRuo0grrTECj7dUv0djccEYSvYuNUvgRDXE5lpmbR0TfLzkfAffdUIXm00iB36lHzD0mqefM,VFyx5RRVeLRVIOE6eJ2pjkPMxdNgku8w0Og2JwmpTWu4rFom60GLbUbRB7XzehL9fsipyST1SydoEG6u8Q6Ig7s7qYOZoX3NkeJtCS3GTus9xWFMOl5l1hMPIB24frVIxSt3ynTOCy6nKHnAdqBTZoLlanyQJLe8vzLDUIRMDD8dYVHh3GsWjTEakGVpXbAM3KWA7h5QCT0RiufDgJZlxm6ddf2NVFaOpme5xkEkEIYqPFKzcBcQ1CQVdFZLxTp2,wTjN3cP18mTfJd7NAOYvvvVhuZ9tCWMo7W6LLWDvvBXiQnpr74NBVWXKVFaUNj1bVZph2PPxNM96NsDlhciiUv9eaFTCYFMrHE80nwQhTp1d6ecVcdqXTmvndqmKmwPYpjR82wUcfxbzYZVT4ZsVlb0NEzpbkisJDD8zXgqQQWz8R99OO3nvisYCseYlmnZgWMXTnqQTNpdSE2SZ24bWzA0YXfF4n0brH1VbRBkdQO2gS5NQot2Ugz5LaBCMH1NT,d5xFkdqVoAHxryA0TUf9YeSOyyRnhDhu9AWzrqirZDbDWprkc6SLFdWFOTBnn4rdSE1CZBTNW9DhRcZXF2JI2t1SHYZDgeeHL8SzID0qgAkXmacqn32iqLNslSmgVB6Qb2WckS3BFsEGqdmkeBD0RzTEvLUQLlrF8nMTzKmlqGEIseSHSHd2khZrujgu7xfiZuyc1UTI0nK9kT6l5XW4BE3eZQ6OUtzbYIkvCsmJNZTDM5zowFhO849pkObJQfBZ,8IB4RFsKAd77Y21ZiEkQoHYUqWXLTsTfPcpFeelcrgoO7KOY1xKz0KEyYiGLc2yFMSPXjEsCghWTaNxLy730F7UwV083g69wWxyMQNU6dMbEBnwpYWgJDPCWe7g8KzHkC4ehebZMpsBozycUThkcFjoeAmijoOynoLy7BHA3QJ03EUkqgtgNKrovlGPh1X1la1t1tPE13io1vuoPFikWehKaGOAlDxX2168ZXFpb7IVeE6Hp2TTbBAxRJMaOkVEv,pPqfxuZOVKXm682sDASWuzQlNAgI6FqmgkT4FF3I690TzI9S9tPGyFsv4AfWxjnB0oDDRG2WCTgjrf0D3hDLkp6BA74mbRQ2G9EYCSJAwAseqYKYVgGmiaQ88YAJl5KZ5udE1R4PFMwIgvb2Y4m1cTiGSrd3mGXNZelTspk2S9tW9vggws3UZRYEcQo8vVnVdUwpFRdnxy4VmV2OZRTvxVIA9HwsBmX5H2hB65MtP3uXp4Zw4eTlE7rfRd8as7xw,gAotW0j2sAaEN3MaTlbmDXBfq5shMWtG8ohkMiSEmVAbjsuWWE2yDsDcRN3Y6NyfidWAAMl4Fxj7nXPj4oLcsNbRmnjBYgkGOUtM2IrQgXI33CyR7FQwt2ox0GAU8ioyV0dpqL2iRYlHkVXmbYxZM2hQWIb3tKYrMoFVH1ECLIuxEGXV20lXNuk3DxpesN217umdleQh8oOSvCbqrVj4Ti7POycVMLb5kiicgNUqvJaL0QubZNyc6CQ3wwZCDi9K,WgO5lHVz1CI8Uq4bWqCvhoXhEZZKFjbYOhCxweQbVOaZrFGxa09DVQjzwwjyYrM6yipXD0gPJjSM5aFabGVixC6BhuI2WxV2NiQ3STQBExGz60KWaSPqzXKizQMGEJxcLpHiQnOk9gG17UUOYZkXNbsAy5iuuasvH2qWaeOS5nsY6rDjXM1FMySUPVa6PLhSDBaiqblzCvLSGSSMCsMVnWNAj7Envn8fRRdDsWx2U0dwGL2WdHXGb4CFlXLel7Cc,iiJYp2PVJuZZsPb5ysW06kIuawOkz2Oq0xINjtNcN9Uu3Od69W7t7rSOvLVrvYeuOXR9vRBtCemv4sfbLrxpY0JPddwOsgOpVO34tndLdMPA5JbUYWHBLRMF1BTygF3FunFeXaImpvwA46m3DrfZB2CQoEGrs82PloS06raZz1mO3Vgll9MKii6DvyMKoISH4jNGIK2OJQ7yWaToOk4sZKdUVaxYdSuj1JkeWC93JbgWZ2JvOPwFy19r03fXSms8,pQwd4S0XlilpLIxAbWwyWJXM0tupXhWkizPQtCg9V05wZpK1C18zyHncwAM7nSnys7g86svI53ROoptTA8E1S8LGpcjVzEZZWScwOJv9WuuAyDoaKZE8uQ6V1S3a6d3DuG5q7LQUTNJsoY0evDIhGYFRSZDsUn8PMpaJzymtiYAnVvPNWJC9ubBHB5ijVuqGy3ND3QYGCSs67EAB4GDlvBYHtiLfXkWoVHMo4SABLTGlRKkuilY20p4O5gQwk7lQ,NVs5xd8OqAS4xgC0uGBKt9a0ZpC33FU4EtyrXGqD4FHN0f1OBhOVxoCWT7nNeZwxL2S7BP18mICLyN1cGw5xfh3LifmNZJ2jpMtFJp0LIjggfmL5RndNafcr6NPXGNqktIkBKouogeDuQuZZS8geSPR6kp0eXKy3JEgykazu41DdEbc0yq7jbhZNNSB7Atcld1tnM4MXSaHa8nhqZvxwIW9TdO0aJG39x1MFctItMKQDxEe2o6DanK7QLPsgnw6L,LEhhwYKge8DjlOY8bfm23erTwk0MWuyHR3QvZ1wTW7jeD3R4A8WVVAqhLynvaSz0z2DDwbFyC5070uIJmIqcVHVrSI2XapnRGCOzcitdWJETSLGGQDP3jcJa3P1RZlW95vBOfTyAZ0HBM2A4eNRNshorkatQE7T920oqLi0NzvQKnpHR7UH8d7OC9qXkEqKrUle7H8rYe3N2kixgXiTCE9ylAKKeX6Wq0aURNP5b49wdJX0VuwmEFCNO8JOjkIJM,V9pT8viYA042nyOhCjvvvuKz7NcfGwW7mPEc9CuTzgNk2gW0j6tzaz0cr5Aio7tzVxtj80QdPkKZ7IkV7eC1baCFZqnof2KVSHmrD6Sry54ki1HzmJcYvrKtMVMBwgYjdvvshBqu1Jdd2IGOpj9Jx8CtijWKuwyr8cPyODXRJa7ECyhfCoXXjykKFEUzFYXBwd9CrPV2txBIOczHL0uzjobBpZuld3JAokti7pLMXvtPFDtiiFhPmBoMrXZbLKdY,N2Yg9DNn3FJRa4RGlLkhc2KsfD6YLl7WpyLphM6rrB2VWOBsYgjUqa3gDFA19I7cLZ9leJMyU4bhwxKVGlhgkjvOaJLt9uPEbIkclB9ti12JS7xCG2VakVQe6SzcCLRAfp2wMhNYhsTpPyEHV1dJ7ivRYllDCYYqVSZGfldefxy1P2oaM3fsLbVEhkN5O4D7QRWulKI3FsBvcc8I78aDGlFdGuw0iUp1q2Sh0C8iQO2uE7SJlWFMNLqXu9nGn5Yu,H3fCEIOkZK9fRXBi8FtuOIA8rMoZpZhOvbpAtXF2IXPG3w70pa7CSbWxze3ESMlHOw43T6VnPBtBI4Zbz6Lqw0VifGoDiNxoQzegQLPrubyPOhd8Of6A97p5f17odt1bDdflkcD3sRPvEllYPBnTUeDP1hssBEd2aUV5tKUEGjWSCCMNIrSEyA15gMExGxJFis6whgkHIEuCsdqi5YW69OcxdFSpZ64W7UHos25ybknwunRs5A32IngrOW4PqZQD,NeZZBRX0QJq9lkXwqghsYFbmdTxveIfunDMT3W7wmR4GCUsGKKNYfp6f9v4acCBabiv5iZEysvmpEUzQ2eAIPFawO2dEydJaYztZj5OOOl76dnJJwl2EMU9ua37qReypmBZ2DIGxyNtGlb1G9Zji7szrMa3HNd2OvUQ14evxNvTeTwNigg5DYE7rvj24F7lRSxmJSraO11vA7t586gIrJV5uPvBhkBObr1Gvhz8ubaodlYgQtZT8ef92PdH7FxDa,td1kGUf4yVbgyH55KGl9nANNRNUCY9RJUOe6MX6ym7jVogWl9Sh99SlAtEYiPkV7qFa1dxwCgnsoSsXDJfPcYoXUDUvvVNhQT4KRSSffY1J1IEEtZLcGuClbVy4gXbYe6zWnDu9ElseFlgWdlMtxwUs4JqG0qIWTX8uXgjdav0rtiyM0rlwQofg5xlGDC1sPCNUUTwOqXIU6Ctiqhf8aWQPCgyzClIy2Rz8TuWkQSRibC2KPSReJxP4znqin5Epr,8NyZ9eypJnAPn9GKztsK3HXKamCTgBVwxhWKL3sGuguAdZ24KmjnsTqXRXnkaryHn9uU8Cydov5x7jVp9VaglB64dcP83z0B5SdI01VS2ZGzpTuLuKmUdayBiywOldTrs38YFeZ1MNfbmtp6tp2UG1fWN9Esx10fmZDTbK4XftJsexfWBGc9SL6OaWIVReB6EcoOyo1gg5tuwMpgkhtmz0xbCpSc7XJvAie78I7HXjKukx8r0G7qTy5wP4X6f6CY,1JThaCFC5LvSr3TlFJby27aw1FTMCNute0NrRH4lSPCGKm4fXB9geJojyL1C67ABNC9CoQYqTy9IIoYsOLy5mhNqdi1DLvY4CiMpC7LcMK1LPV6K9hjvEaaTPvOO9ZR5FrNE2pUbL3sLxs8OHZmX3y100nh0yqh3xjXODzCzceA7dqVamroRYdDs4jCWqcqWrmuQEknw2KEYUMF87rjC7EOdt8qVhoTuECWEkmG9lPPBdyZotxZyes2NlyhZDuVG,fjNQXpkOqJlH7IEU1Y7ufY0DGZx5STrBxfdljqJ07oHQqgfzUlSRHKsVWoGrGmoMMAcM5LvZJFIDwHoDVACDuRIHdAmuu9exFg3F8LhU4PUfS5GZe3io6CJtKxwmLXs9JPpTw9Udv8OiQadpvFciJ5WxLPs1SbXJ9SCrvsRINFCi4m2SoKuFn4FZmNKgMq4505A3crig0Pq5iVoARyKFhZtg9rK3RPZlUXJkIZisjRMOuAjaMjkp6iUA8cve3VjO,2jnr7YUOCN1amJV2IeEWGgnmQQHBrWwZbFwGUmFfNKGue4vtU6Erl0tXNcOBTE1fK7BX2QfuAhdmK9tw0j4H74H7t9noh4IjDAPV92Ep3Mbz8YARUbR3l2RNEQZuPAnZY6r9Fe2aM2eeZlIatq46itBWdHxH6hmtLurrPwBkQbEpmR2VeaYl9xTLpCbEINrLwZTGpDAL12c3gCkJ6FxXfurWliyB4UEbEwPyzBbdUB4k74LNpJbw6Tu0QAEfAimT,DiGbB3ZqC1P33ZZuOu6WHX9HUee20TpMv99L3lyh3FaVI030Z7SgWqpwAvjRQzOsgtNPcKce1eWwRY9Sj5N9ZOZXGwI8wow0kONht05hiuVQsOuQPhGBtOzvxZmceBL8Dx8ermNcAdOOHpgEGQ8IrS9Ipfjov9jDpK6l2WRZdwQDhssU9rjVBAqmCwhjpMLluLVYvrdh5wZe0niKxEiqGYeek1am3sODT6zhwOUgx2sz1YRFJlPfj8xjf9kP033j,ftQj6A773OidkgdKQyyUqdYXDHkAdVGGpzbFiYWIkAFdoxRjeratnJMf8LbKTdD3nUVx3iClaHLBQSar2B3VLaR6T9RkFyvi8RGG0vdoKvmHHef9iAYmvwc6ViXmknsBG5A9L6HpgytfGO6v4OlRQNxrZWzKHxDSfeSlpeqlyXi3r2mt90vm6WEeKU0x8egva16L2CxjHj3CHlHR6ZV1amIieh85h3faJW6lZfBBu1ZyptKH3QMgiCWPE7CXmnpB,HGq946SlTnBH6QsSIQeAmtSHTGJNSvhFG2fxNZphJR5bNtnjNj4DU5wfe5CNFxJRlI1dO5hRDmmflgg2cR7BYQp3kOr0qRsmU3jAkwUnzmbOSzgf1YqBUAodA1KKvROTGk9uGy9HcUHDPpOkdlJMM20WSgUZonsUAdUJwlsSoDc0SnluUBxo4qe6nm2waClUo8q6o5JJ6TnwL5za9I5Jimh1ntZJBzf9qwXvtDM4IWulwClxdfpGz7t3nTEpbXeG,Cv8w2JnKMFRWb0nLk6T2XoeiGryswsv0qGdtQMYm40xDn5qY0L9MB4KlK6pMkQMhVJJ4uPn3NyZjwgEYu2gwHsneJZhDdfB6ScX4kTNpvHF0yDRmIHilJJVCQqCwPPjEIhOjMkTBpiX2UqyZGzSnUMDDUmFUZo96jnTF6e5vkhLhh32IOYVAmutbvQMdLLIFEHschydbfFz8FT26pDgfa0FrUsIQHZjSmbFOzgkllHZ64aCvmZu3pNwcb1zSL35X,KwkJ168d89WxwC7pQdjcjMMPvDseaCE6iaaa5CVMJra6f9fEwEweKrTyqQnLFAUroeOz6S3NDYgEg3LAqf9ZHLD49raedkYfWaV7x7xaMznCWVKdNqLmDAPE9Ot1ckwFocU4DPqkGEr9dqe5wBjuQxcaC7zqBGrJM1IHMsJHXQAJUF6bwHRBOQGrieSSQTN76JkZ5qO0JuSH25oi28aDhofkYUcwQexXsotgd7ez5JKrYEpMrj0XET7YjQ9A1oeS,9sVHf4oBeQTHmPDCmsR2f4fmrSH2P47L4ugzPWS5poce4HlZZsXMl04evY8nTB7KKiK4O8ijWVMGMZWsPu5KH0xl7BdE4eI0ofLeLPpyCmHCbYg9EANIV7Im4LbENmNIqug6EdMWev4V9bGb3ZY2ts635yaBTX1bJauRlwLVkPzvwoCPLOfXh6JB8pOctZlfqlc35ZJgYk8WqHYTdKoq0VyzWZADSxTU4FiTcJeGHxtFtFsl4Mx7B8P22midHm0p,dGOPshJPIdaASRUllWveYsLJSPQJ6MIAkO06jrxvmyGOEA28xWu5mvdlGV96dVa7cERngQY4Lk830Gy8EDPHSTK0jUIZRjb3PMM8UxlmnFnVMR9fypUPSIU8uqmOHAcGIf2F4ULFQ0mTQgYNBxgYqO27WuA7c79GZ2CdVqSiTw8gdo1IG8SzvjjTuf2smZwFv3Fger8HSbNBgk6C18Bk7thwhveSF2yw2vCF4WGDgwMU3P6ShMwP03XZTGwxnfkY,HoI6a7NkRbU9AMV6dPzsXk6t5U7pbVwVxIMOQPgjzBof14jIXNQkXKXgo3MijWj3HdTK2Gi0SYGtwY7pqvU1Ahtp7GZDsfFiToDlFQcC8WYBYSuItPHgOHlaPYkuYJJqGK0t5EYWvSdec16lkTPGlpXRER1cmW7gvQJV51VbO4hG8vLE0V6283DvYjcM73OeQACs0c9Vo3Q96ePOnErclFIpTWQcRhXIRYMlhrvQXdzBuUQzvb3L36wWiCIGpmiq,CkM9TBvZykP914NE2zTzhLhNrvjjeEljgbD1NmnRN3MF7I28WhhysLwTJSzAEQGtx45A91HuuavH7mX3niZnIr7MwgbKVaeqcHp0JnLURyKbBdefqkTEMJnF2VZTunzUAkoUGhbVP143VpXLhar6gPicSA9G2YZr9VfMTbQ6VbNvCsyHmHL4wfoQEe1xNkXEQmCgQA5VY3KlFwXuv90hbqgGpeHKePiRxao5vs1PmITwDKHeAfjdf1jP4EWc52Td,tCKbamVBZn4MAnNsIDTWMIWfLksXdjeq9Ns9OC86zk58zCjVmcbKLiq9AHxxd0zkSZLkZcq4l0RtfzkMVQL7xTJiezVXkkQ0D8qLtOj2rAQOWmVq5BbKwwfCbdLqgQSZ4OJcOpU9V92VU4i08DJWyJ9KOY4VU2IT4FqRBkTb4S5qHuztbfQxl1zcU4MofIkAhZUmeo1898Vihf7rts7eTppEUrBzzreZLthR8yOX0nD90lLYBrMhJ5KewtWvP3C5,tyeYbW2GZ8rdaq6f6KYZc8uTBSsjCF1A4HDmoo6wdchtdarlmslCQvmxvSTpcyR4uZfvSwOZI4qEp2avMoqM5uv5fwaaaHMvwWJuBXvXixLgUm6DRfFduxTNohssIvnqUbTZRaOceAQAMH6BTHTiiVOTOdYzsTQMSZG5JV3DvcPov2P6Vtn2M9oESfgWyuI05c1qy2nlPAmGb39sNsi5ly4VywLhsRncOXDXTrXYHsqVGD7oMN8LZTUmbq5H8tDi,UzF4PnK24C635YzenkGnKns5ICpbtiiitOE7khnLc1D0rthRKrcMyAEuFnp45gbOqOtLDWAyAoVEbNXAGfeIQRZjKT89bIFdrff0EgFE56Xk7Xf0ForWtuLT3MyadNZW2m5X096PifLTd5LZWGpxqKJdfFe7MUH4yEdwvxEty2zQ2uSLzEI6gMervbxeGmTQWXj7DQRuifNnuFNp4uada101GiizD89SQdCbznQduQQspsyIMfQFChu2X1NLt9lF,QikW9spY0EYXK6Y6vT61UUo9ApA8wrXBqNCiR6OmTp8mj2EmelYgJUd9LM1EQYPupyrjyiPH14ILdfIm5NrwuVEk25HYV4UZy4X5QEccjW3hcSDhdraACJSxy04w4Sm5ar4236eExYeiCKmjnoKXV4bqpCuezkqokzYPWy8V1Q1JZNV5K7whwMkPbLMFc2SfcmfUe35OgQk1QueGTvCpcKNYThlqYiJOUw1cLo0AxDrS38jUIBfvNVQAeSe9Bvqh,lO6285HzkYiogum5MXUrV0Y7OPHOAPeAfxIbaa1vfaoQtnwlZ858ZAMBVcF9gdCHGarVfo066znQPXasp8ZHuAPhW0qBT31vDFntbfmoweKWDCZReQP3SY2GBq19prNFhz8wjUPXvQalR3WFIUnxAbAVGKJ3lZOBq8qSysHOShVwaqqmUcNLcan6IrzVYcWm4Ng0RQpaeuVgLv5d1G77buLapc0r1ijiSAFEd5XX2c61c0mpEQZxK9TlBhVRi7w5,f767Vz3RmvxUrMKSpcl5XAsL5E1c5PLHzcjgBZvI9PKuuJKk2lfaRrIDhy5UsVoRmOGQiDhkgRsopiXOMxtd826HyRE45J735ZLJe79UDsAokpWX9OkV8Gtshat9GOIQz6LuZLMc5f7cl825vlAXCExiuV4BFYFJKIYmxc15zS8t75sljj7dLnbTW9flJAHk4WfIhzWwG8PjeuTkzr031c6ZHYoBocLChNohluPHxivpMbqMMkEY9gpXGLCdPbog,G3GOm5X8QodKj2rrX7mZhpnsWLLhKYZsYjXNfFlRjCtEENv1mwu564N41mYmtEvugLXD5KNr6qFCIzMPzEG0kN6lchsEix6fComPpJ0QMMmkSRxEYae1af5J8MrFln3sgpgIBXnlNgAFWaguxkHyqUmokgOgJMQEuG28UbRp0201rHqaGxzzQd4xXzeAjhwK7CoVEUf1vrZDAOrxMmW0ycCOg30HJ2b35gPiTAqIv7mllH26lPa57ss3f6G2UZuz,tCtJaUW95cthEyygfrtKqkyg2PivLo5aHKjmKKX8Ai9OrfXsspOeQJlApQJPDSLkDXoxo1zzUVGZoYn0W0HxA9Xmum58nQ1XWwva0ddVQ1abjPY8PiNsKPbcPQYriWBBhzoX2JUHQbLmVDCWI6bkoGm3Z2J6BOmz2NtjebxAmvJLhfaMXOWpHtDj3zybu1W70W5SqS7Gq5poe3bEBDiW017uybjFVxq0AibPjgeGLiRNdPbu2NTd4lmdkZUw66D3,aJgj0eVyuRk1f7JD0r2pwf6D0vEoWplkAeFxSSrzHO7qbf5ZdjjcuvlhgLtb6wZJivODVdKmFEmp7i3KZ0sxd3k7cBtQJ8LIQoPrhyejmDOMa2T9lQS0KgvDxb6bZzww0RK4IPMbgvI4mebABxqBV6UmKTs5d9IuyAP89wOns6fbARmvQOQLp5TGE5VjYccb6xUn9VquW5kHKiE7hWXUR8858Cci0xE3UWOtd2vClKb6Ju065EL4QVp340YnFUKv,9cy1U98ExmjCFXopVgNx9veycPwPB5Q1xcFmUnMtdRgd3Y9hMe0MXB643pul4ybkQ3QN5bYRCB0SSqhSJPiHspMB6v3r3Y8frtMzSe7jXIbifwkpwhigOkBEivtb7sLexgkJFro0reU6U9FDbwHtPMpyQ9kgkrHTGEXidkdF20Mk20olLH1BV6rkRgmLmsfV9bPhKvD6GSgTPHcf2dl1J2YzTvy6srtekJvIVyzBITPzoXrlankz5umlkV6WFDUh,eRXmOYVQikV31bwxbaTmtoexrOeh6sMttjEtYeh3NzjwYYKWqXMXfWj0IF3yho78b3esFTOGCOC0B9V59qZppuMo2znWyi1E9h44MzdGMWCw4hpYjLCldMYYN0a566plmserVEPdJuPgR99rc8bmAGwG7oT1iHJJKEeiuFDekpSHmXVun0cByHjlKeHPrmG4JElMflY9AO3chPewjG4iJylAcQ2a1pxIjGBAR8WGf9Rps5vdmSQ9cM1vcnKVkiE1,b8Xw0VApdGybxWGZgxYvEwGCMk3cbTaH4HFNMN7aC0OvBLkyoW7fwHZYOXPRHUH6MqOFXkZQLXes0blgpmSxID31zxXJ4TUYtftRyjcOJA4cgsKHvObYg0aVACQ6ZXmsBsmXMYig3lkTUEGDwpsgGY3HviimBppF8tYrm7UT7tuIidIY0WdkiwGkAU3iucbMFPNVezNkmi9okkU6nq9mp6RGpiH4FPOOPJjFudisEkRdQ98jfnRMYKdHVFA3TOjv,ctn4RkDKnSevdAmedEFp2Mfxks2VAhoT1rfv2OKljkcradCe9uaChMYzmMBzPY9kWaYEaooqmCRFLPnxHYfLXQZPoyq2llpJUS8JpUftb62qJeh3Lgmf0tz6NRlPgzGVk4dG9H4dnTNvFwcJS4WuyYCqRWGxQp4krAdb4qejt0iRd5Kb6aHxnIGqQ3KzzoeOP6xfPOWwfF383aXt4y3CnDyGZNhySjWbiS5hUGq0MAsxBblEG50DcJRQnQgFaWoj,UyJTVJMsiujdpZzXnE4lxQmsywkcqHuUjU9DiB7nD6usb1z9foAyDaaspr09Lqwz04vDNNJmEP1kEAW5PyF0xdGRfp5xJfIdtcwzoiEX1gMSnu9WyFP1B6OHAlM4UXdwq4kxninwvhI32ocyvCFx7nIq77UL241OZKX2bbimX74kUQGcfW8o5rax5HmtHmrD3DbRKjiBRhBpqC7LWSDuksCSmdEaA7SlkuU2DZTErHG2PbjhT7WWGAiV5nItQ6wk,lNiUegN6VK5mGcxJx1nzMym6FMTCzkIqFwPLr0FcFkgjriC7W7VdL85LTwvkdjXaIxEoCfTeskIwD4'
2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
,ok 96 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 5, 7, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [4, 5, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 06:50:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:7DC295B6-5886-44D5-B750-7B97D55E9F06
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60543
[ThaliCore] Session.disconnect() peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45717B12-6A7B-4A44-B673-96CD3521F8C0
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1278CD6B-3495-487E-91D3-B225D2EA,3365
[ThaliCore] Browser.startListening
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DC295B6-5886-44D5,-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEC221C2-D82C-4FE9-8F21-083998DFCE02, (syncValue: UlFTMDCMAMBclo1v4k6BjGs4OX9THzhZ)'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","generation":0}'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","generation":0}'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,C221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,EC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,C221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,EC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,C221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,EC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,C221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FEC221C2,-D82C-4FE9-8F21-083998DFCE02 error: max retries exceeded
2017-07-24 06:51:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UlFTMDCMAMBclo1v4k6BjGs4OX9THzhZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UlFTMDCMAMBclo1v4k6BjGs4OX9THzhZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:51:10 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-24 06:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-24 06:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7DC295B6-5886-44D5-B750-7B97D55E9F06 (syncValue: jbOvefh,qKJsJifexO1QHk82nTS6bdcKa)'
2017-07-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: ,0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7D,C295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7D,C295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jbOvefhqKJsJifexO1QHk82nTS6bdcKa","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jbOvefhqKJsJifexO1QHk82nTS6bdcKa', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7DC295B6-5886-44D5-B750-7B97D55E9F06","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:51:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE (syncValue: QzwaC6qgT2CQJ5xCwPZVzhb,f37Jzb1Ws)'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C583F9D7-EAC2-4E43-AC34-7A26B,B7DB3EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60568
,2017-07-24 06:51:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QzwaC6qgT2CQJ5xCwPZVzhbf37Jzb1Ws","error":null,"portNumber":60568}'
,2017-07-24 06:51:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QzwaC6qgT2CQJ5xCwPZVzhbf37Jzb1Ws', error: 'null', listeningPort: '60568''
,Connecting to the localhost:60568
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 5, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:60568
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 06:51:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-24 06:51:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4, 5]
,2017-07-24 06:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45717B12-6A7B-4A44-B673-96CD3521F8C0
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60568
[ThaliCore] Session.disconnect() peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199
[ThaliCore] Browser.startListening
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
2017-07-24 06:51:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE","generation":0}'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE, (syncValue: sIEg7i6kdkk316u2hCMQBmwqYg7CTN9d)'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7,DB3EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F","generation":0}'
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","generation":0}'
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","generation":0}'
2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,83F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,83F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sIEg7i6kdkk316u2hCMQBmwqYg7CTN9d","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sIEg7i6kdkk316u2hCMQBmwqYg7CTN9d', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3720624C-71F8-4A6E-A942-2A1B9013449F (syncValue: T7wPQiJpECQvZQWOinnlNAv0ntS3jBfc)'
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60583
2017-07-24 06:51:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T7wPQiJpECQvZQWOinnlNAv0ntS3jBfc",,"error":null,"portNumber":60583}'
2017-07-24 06:51:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'T7wPQiJpECQvZQWOinnlNAv0ntS3jBfc', error: 'null', listeningPort: '60583''
,Connecting to the localhost:60583
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
Connected to the localhost:60583
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 5, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:51:33 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 06:51:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [4, 5]
,# teardown
,2017-07-24 06:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1
2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3720624C-71F8-4A6E-A942-2A1B9013449F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60583
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T7wPQiJpECQvZQWOinnlNAv0ntS3jBfc","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3720624C-71F8-4A6E-A942-2A1B9013449F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CBF611CF-B265-4BCE-9323-7675CA9B50FA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CBF611CF-B265-4BCE-9323-7675CA9B50FA
2017-07-24 0,6:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA170DBD-B96B-41CC-B4D7-AB72E3BD0AD9
[ThaliCore] Browser.startListening
2017-07,-24 06:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B8E3465-C24B-4093-8FE5-81825C4AFE05:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B8E3465-C24B-4093-8FE5-81825C4AFE05", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CBF611CF-B265-4BCE-9323-7675CA9B50FA
[ThaliCore,] BrowserManager.foundPeerHandler peer:Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserManager.foundPeerHan,dler peer:Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
2017-07-24 06:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] Browser.browser(_:fo,undPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
2017-07-24 06:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"adver,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
tising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-24 06:51:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D556ECF-66EC-4B00-86CD-254C8DD5282B
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20FD2668-13D7-4869-ABAD-21063EE2E0E4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:20FD2668-13D7-4869-ABAD-21063EE2E0E4
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:20FD2668-13D7-4869-ABAD-21063EE2E0E4
ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 06:51:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:35f892d4-38fe-48d5-a7d1-b571306584c7 error: startListeningNotActive
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jMHBY2FjsvSbWjkZJdNXZGa9xs9vUONx","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"35f892d4-38fe-48d5-a7d1-b571306584c7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"35f892d4-38fe-48d5-a7d1-b571306584c7","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C8C2BA9C-2537-4121-B0D0-537A2DE54D4D
,[ThaliCore] Browser.startListening
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 No error on starting
,ok 134 Got null as expected
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"blT9Jsl4mSbM30RhvN6Vin6cR5hH7twW","error":"Illegal peerID","portNumber":null}'
,ok 135 Should only get called after multiConnect returned
,ok 136 SyncValue matches
,ok 137 Got right error
,ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 06:51:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E04725B5-5AA8-4B87-8EEC-5C334D4F4725
,[ThaliCore] Browser.startListening
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:731665d2-e7d0-4580-a084-b118cd3e94a1
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A69943E-B08F-49FD-A918-3969D49A99E8
2017-07-24 0,6:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:069CF3E0-E96D-4C52-9D94-C8E196CCDDF1
[ThaliCore] Browser.startListening
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8F45B80A-27AD-4221-BC31-4CA963D9A182","generation":0}'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8F45B80A-27AD-4221-BC31-4CA963D9A182 (syncValue: 35gYNjgM4njnz1AUTXAmHWLQSPQo7Xo3)'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
,2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD","generation":0}'
,2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
2017-07-24 06:51:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","generation":0}'
2017-07-24 06:51:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:52 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:51:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8F,45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8F,45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:51:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"35gYNjgM4njnz1AUTXAmHWLQSPQo7Xo3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:51:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '35gYNjgM4njnz1AUTXAmHWLQSPQo7Xo3', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:51:56 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"8F45B80A-27AD-4221-BC31-4CA963D9A182","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8F45B80A-27AD-4221-BC31-4CA963D9A182","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD (syncValue: Pyy3LLnrF8rPpAyPzQX4dZ8wf1azPmz6)'
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:51:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
[ThaliCore] Advertiser: session connected Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60596
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Pyy3LLnrF8rPpAyPzQX4dZ8wf1azPmz6","error":null,"portNumber":60596}'
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Pyy3LLnrF8rPpAyPzQX4dZ8wf1azPmz6', error: 'null', listeningPort: '60596''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 5, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0) found active relay
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JY6CoAtMMaiFhrjFQ6E9uTQO55TICTlY","error":null,"portNumber":60596}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0) found active relay
,2017-07-24 06:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3aniHRaQXSv6XgrsOpzODtRyK3LCBWAx","error":null,"portNumber":60596}'
,ok 149 No error
,ok 150 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
,[ThaliCore] Session.startOutputStream(with:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 5, 11, 12]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,# teardown
,2017-07-24 06:52:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1A69943E-B08F-49FD-A918-3969D49A99E8
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Advertise,rRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserManager.disconnect peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60596
[ThaliCore] VirtualSocket.closeStr,eams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted so,cket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [4, 5, 11]
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:11 [4, 5]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Pyy3LLnrF8rPpAyPzQX4dZ8wf1azPmz6","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-24 06:52:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,[ThaliCore] Session.deinit peer:E6C70DFB-2433-4ECC-8251-0237DEBC87B6
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'listening 60600'
,ok 151 Should throw
,# teardown
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 60602'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 60605'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 60609'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 60614'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 60618'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 60622'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 60626'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 60630'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-24 06:52:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed',
2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 60682'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 60686'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 60689'
ok 198 port must be in range
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 60690'
,ok 199 second start should return same port
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 06:52:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:15 - DEBUG createNativeListener: 'listening 60692'
,2017-07-24 06:52:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
,2017-07-24 06:52:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-24 06:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 06:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 60694
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:577FB140-91A3-4526-AC67-8110F8393314
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","generation":0}'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59D3765A-2BC9-445D-A1CD-A98041FFB854 (syncValue: EoL5gJfLoEiTToUZadQJKRFiOWCUpTGD)'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
2017-07-24 06:52:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58BABA89-9A63-45D3-9381-F655C03EFBAA","generation":0}'
2017-07-24 06:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:18 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", g,eneration: 0)
2017-07-24 06:52:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","generation":0}'
2017-07-24 06:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running ,test!'
2017-07-24 06:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,9D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8
[ThaliCore] Advertiser: session connected Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,9D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E
[ThaliCore] Advertiser: session connected Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,9D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:52:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EoL5gJfLoEiTToUZadQJKRFiOWCUpTGD","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:52:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EoL5gJfLoEiTToUZadQJKRFiOWCUpTGD', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:52:24 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:52:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"59D3765A-2BC9-445D-A1CD-A98041FFB854","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-24 06:52:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:52:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58BABA89-9A63-45D3-9381-F655C03EFBAA (syncValue: 2nyZHgX0Tp5lJZzAU5RhmiL,y68OP3xzl)'
2017-07-24 06:52:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58BABA89-9A63-45D3-9381-F655C,03EFBAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60706
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2nyZHgX0Tp5lJZzAU5RhmiLy68OP3xzl","error":null,"portNumber":60706}'
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2nyZHgX0Tp5lJZzAU5RhmiLy68OP3xzl', error: 'null', listeningPort: '60706''
,ok 212 should be equal
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A8E8C04-7FDF-475E-B232-F97B78C2F1BC (syncValue: xxTnwHPxdOWzF3e7UkkOyJkhCi1ecLEu)'
,2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60710
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xxTnwHPxdOWzF3e7UkkOyJkhCi1ecLEu",,"error":null,"portNumber":60710}'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xxTnwHPxdOWzF3e7UkkOyJkhCi1ecLEu', error: 'null', listeningPort: '60710''
,ok 213 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:577FB140-91A3-4526-AC67-8110F8393314
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:58BABA89-9A63-45D3-9381-F655C03EFBAA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60706
[ThaliCore] Session.disconnect() p,eer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,[ThaliCore] Session.deinit peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:60710
[ThaliCore] Session.disconnect() peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListen,er.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 06:52:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 60712
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] Session.deinit peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2909281D-1594-4825-9D81-6E148BA659E3
2017-07-24 0,6:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F
[ThaliCore] Browser.startListening
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","generation":0}'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A8E8C04-7FDF-475E-B232-F97B78C2F1BC (syncValue: PBBGE6Bn0DRayWQMkW1Qye75rxX03L7t)'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PBBGE6Bn0DRayWQMkW1Qye75rxX03L7t","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PBBGE6Bn0DRayWQMkW1Qye75rxX03L7t', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABB6C619-722B-4372-96F0-259A80A2AF24 (syncValue: MuCa050RgEg2mR7c24wsl6e6G70rEFbu)'
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:52:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60725
2017-07-24 06:52:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MuCa050RgEg2mR7c24wsl6e6G70rEFbu",,"error":null,"portNumber":60725}'
2017-07-24 06:52:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MuCa050RgEg2mR7c24wsl6e6G70rEFbu', error: 'null', listeningPort: '60725''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-24 06:52:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8E536049-181F-4A81-B849-449127FF5604 (syncValue: vgRreXkJfz5TKRkc44zZPjm8SsoctIMN)'
,2017-07-24 06:52:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
[ThaliCore] Advertiser: session connected Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60731
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vgRreXkJfz5TKRkc44zZPjm8SsoctIMN","error":null,"portNumber":60731}'
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vgRreXkJfz5TKRkc44zZPjm8SsoctIMN', error: 'null', listeningPort: '60731''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] Advertiser: session connected Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
,[ThaliCore] Session.session(_:peer:didChange:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2909281D-1594-4825-9D81-6E148BA659E3
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:ABB6C619-722B-4372-96F0-259A80A2AF24,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] Session.session(_:peer:didChange:) peer:D0DB2693-5B34-4DA5-BC9F-9E7155967001 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2909281D-1594-4825-9D,81-6E148BA659E3", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8,8AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60725
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60731
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] Session.deinit peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:52:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MuCa050RgEg2mR7c24wsl6e6G70rEFbu","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'listening 60735'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B4344E27-F5FC-4E0A-B057-EC0AF40CB741
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:51 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:51 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'listening 60736'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F048B095-3A04-44D0-90EC-5B44A480ACFD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F048B095-3A04-44D0-90EC-5B44A480ACFD
2017-07-24 0,6:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F048B095-3A04-44D0-90EC-5B44A480ACFD", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:F048B095-3A04-44D0-90EC-5B44A480ACFD
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F048B095-3A04-44D0-90EC-5B44A480ACFD
,[ThaliCore] Advertiser.stopAdvertising() peerID:F048B095-3A04-44D0-90EC-5B44A480ACFD
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'listening 60739'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 06:52:52 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 60740'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8DABF484-2C03-4C90-80A7-1FE7550B6BB1
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6AB72D7F-0EB8-4C48-A4E7-118C3B066B09", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6AB72D7F-0EB8-4C48-A4E7-118C3B066B09
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6AB72D7F-0EB8-4C48-A4E7-118C3B066B09
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] ,B,rowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discov,eryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07,-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 60743'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F08563D-12DD-4954-9EF9-BE828A26D485
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79881EE0-7D12-4799-89B2-48BB6BA5D992", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:79881EE0-7D12-4799-89B2-48BB6BA5D992
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
2017-07-24 06:52:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:52:54 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79881EE0-7D12-4799-89B2-48BB6BA5D992
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 60745'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D15FD08-0A01-4C59-A979-AFF309BBDFEF
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA71C126-1F4D-41EB-BFCA-2A07A9BB8676", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FA71C126-1F4D-41EB-BFCA-2A07A9BB8676
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FA71C126-1F4D-41EB-BFCA-2A07A9BB8676
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-24 06:52:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 06:52:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 60748'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:31D5C071-1CA5-47CB-ACD8-CD9711D23440
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 60749'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BA273BB5-FC1F-4804-B859-EF0CEA010F76", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BA273BB5-FC1F-4804-B859-EF0CEA010F76
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BA273BB5-FC1F-4804-B859-EF0CEA010F76
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 60751'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 60752'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:64CAB8B8-AB9F-402F-97D8-697491400229
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C2BA88D-2A6B-4A6B-83C8-0EE490DBB1FD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C2BA88D-2A6B-4A6B-83C8-0EE490DBB1FD
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}]'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0C2BA88D-2A6B-4A6B-83C8-0EE490DBB1FD
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:01 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-24 06:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-24 06:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-24 06:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'listening 60754'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:52C68463-0618-4ED7-A9C9-4CE393CD01D3
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}]'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35007D94-7682-4602-947D-7A22EA1AB0AF (syncValue: RBGcDUmIJYkJ2gA4yPEvfn2KNMaaiYFU)'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57D5CC84-0578-4F84-9A1C-FCC81840B6BB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57D5CC84-0578-4F84-9A1C-FCC81840B6BB", generation: 0)
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","generation":0}]'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}]'
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","generation":0}'
,2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:53:07 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,5007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RBGcDUmIJYkJ2gA4yPEvfn2KNMaaiYFU","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:53:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RBGcDUmIJYkJ2gA4yPEvfn2KNMaaiYFU', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 06:53:07 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:53:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"35007D94-7682-4602-947D-7A22EA1AB0AF","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:35007D94-7682-4602-947D-7A22EA1AB0AF
2017-07-24 06:53:07 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-24 06:53:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00 (syncValue: n1H0IzbEVnrOuCd4Oau8ZrS9Kihn4kJ3)'
,2017-07-24 06:53:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:35007D94-7682-4602-947D-7A22EA1AB0AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60758
,2017-07-24 06:53:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"n1H0IzbEVnrOuCd4Oau8ZrS9Kihn4kJ3","error":null,"portNumber":60758}'
,2017-07-24 06:53:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'n1H0IzbEVnrOuCd4Oau8ZrS9Kihn4kJ3', error: 'null', listeningPort: '60758''
,2017-07-24 06:53:10 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 5, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:11 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:11 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
[ThaliCore] Advertiser: session connected Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
,[ThaliCore] Session.session(_:peer:didChange:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
[ThaliCore] Session.startOutputStream(with:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [4, 5, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:52C68463-0618-4ED7-A9C9-4CE393CD01D3
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60758
[ThaliCore] VirtualSocket.closeStr,eams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er removed virtual socket vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] Session.disconnect() peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:13 [4, 5, 14]
[ThaliCore] TCPListener.deinit
[ThaliCore] AdvertiserRelay.didCloseVir,tualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [4, 5]
,[ThaliCore] Session.session(_:peer:didChange:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:20 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
,# We provide notification when a listener dies and we recreate it
,2017-07-24 06:53:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 06:53:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ABB6C619-722B-4372-96F0-259A80A2AF24","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
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
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'listening 60761'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 60762'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5E54E37C-D1EA-48F4-80FE-229823D4B822
[ThaliCore] Browser.st,artListening
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
2017-07-24 06:53:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 60763'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EF0D294B-AFFB-46A4-88FC-7F375A08CA99", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:EF0D294B-AFFB-46A4-88FC-7F375A08CA99
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EF0D294B-AFFB-46A4-88FC-7F375A08CA99", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:EF0D294B-AFFB-46A4-88FC-7F375A08CA99
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should, be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EF0D294B-AFFB-46A4-88FC-7F375A08CA99
,[ThaliCore] Advertiser.stopAdvertising() peerID:EF0D294B-AFFB-46A4-88FC-7F375A08CA99
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 60766'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 06:53:24 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'listening 60767'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 06:53:24 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 06:53:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d387d1c6-e441-4efa-be15-20eaa47bb336","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
,ok 345 should not have been called more than once
,# teardown
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d387d1c6-e441-4efa-be15-20eaa47bb336","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"74c765af-d9f5-47c2-aac1-16f3135e59a4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"74c765af-d9f5-47c2-aac1-16f3135e59a4","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f10f68e3-2224-4ee5-b961-0c70038a0e7a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 peer should be a,vailable
ok 363 cache contains wifi peer
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f10f68e3-2224-4ee5-b961-0c70038a0e7a","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7a9415ac-a91c-4023-a38b-cfe0b3a2be7a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a412e15c-4672-4ac7-941d-98086fd6127c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7a9415ac-a91c-4023-a38b-cfe0b3a2be7a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a412e15c-4672-4ac7-941d-98086fd6127c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"19bb0fea-5ee2-4e33-8e78-1057858410ab","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"19bb0fea-5ee2-4e33-8e78-1057858410ab","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 06:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 06:53:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fb03a828-9cf5-403f-94e3-f57a0470beae","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be available
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fb03a828-9cf5-403f-94e3-f57a0470beae","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fb03a828-9cf5-403f-94e3-f57a0470beae","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'listening 60768'
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44fcd654-e54a-4dac-8d60-e12f3c8ba359","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44fcd654-e54a-4dac-8d60-e12f3c8ba359","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44fcd654-e54a-4dac-8d60-e12f3c8ba359","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 60769'
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d5649055-9587-4fd4-9f2f-aeaaee010b75","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d5649055-9587-4fd4-9f2f-aeaaee010b75","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c6835e6-87e4-429e-a0e9-31b1b2a2a61e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c6835e6-87e4-429e-a0e9-31b1b2a2a61e","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer, should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 60770'
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f4dbb131-eba8-4b86-b0ae-e91fa4b92cbb","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6107b4ab-8490-4f92-8cb3-a94566e5e614","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6107b4ab-8490-,4f92-8cb3-a94566e5e614","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6107b4ab-8490-4f92-8cb3-a94566e5e614","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6107b4ab-8490-4f92-8cb3-a94566e5e614","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f4dbb131-eba8-4b86-b0ae-e91fa4b92cbb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 06:53:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 60771'
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"15b7ad2e-0945-40ea-98dc-e0d551608c51","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f954263b-6daa-45db-a4ac-0200203761b7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"15b7ad2e-0945-40ea-98dc-e0d551608c51","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f954263b-6daa-45db-a4ac-0200203761b7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 06:53:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 06:53:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72ebb814-859f-4c9a-8851-17be7cbf78ea","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72ebb814-859f-4c9a-8851-17be7cbf78ea","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 438 address has not been changed
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72ebb814-859f-4c9a-8851-17be7cbf78ea","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 439 new port handled correctly
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72ebb814-859f-4c9a-8851-17be7cbf78ea","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72ebb814-859f-4c9a-8851-17be7cbf78ea","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 06:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
,ok 446 error should be null
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
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 60772'
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf6b2f52-e627-4d02-8af9-3da1ac07059e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bf6b2f52-e627-4d02-8af9-3da1ac07059e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-,07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 60773'
2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39c7d7a5-0e00-4de6-8993-15bc3fbf9be8","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:39c7d7a5-0e00-4de6-8993-15bc3fbf9be8
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 06:53:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39c7d7a5-0e00-4de6-8993-15bc3fbf9be8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
,ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 06:53:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 60774'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D99255C7-4015-4CD9-BB39-77247470F4D6
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"47653bbc-a83b-40b1-8594-b6fc29160d82","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4870cd8f-9fd5-46e8-b64c-8564863a05c7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"47653bbc-a83b-40b1-8594-b6fc29160d82","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4870cd8f-9fd5-46e8-b64c-8564863a05c7","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 60775'
2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e42d0d8b-e979-45f7-af61-cde441070a07","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"601b2083-7d08-4bb9-b782-3e88f965f930","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e42d0d8b-e979-45f7-af61-cde441070a07","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"601b2083-7d08-4bb9-b782-3e88f965f930","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 06:53:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 60776'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
,[ThaliCore] Browser.startListening
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00 (syncValue: 0)'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8A,AB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}]'
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","generation":0}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:53:38 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","generation":0}]'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","generation":0}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
2017-07-24 06:53:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}]'
2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8A,AB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for EF040FDE-0D6B-4D8D-A867-F3E61402067D (syncValue: 1)'
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-,2,4 06:53:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Advertiser: session connected Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] Session.session(_:peer:,didChange:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] Session.session(_:peer:didChange:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60782
,2017-07-24 06:53:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":60782}'
,2017-07-24 06:53:44 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2E94013A-F1F3-45ED-A4A4-58C18682083B (syncValue: 2)'
,2017-07-24 06:53:44 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 5, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [4, 5, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:53:44 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:44 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
2017-07-24 06:53:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
2017-07-24 06:53:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:53:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60787
2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":60787}'
,[ThaliCore] BrowserManager.disconnect peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8E536049-181F-4A81-B849-449127FF5604 (syncValue: 3)'
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [4, 5, 15, 16, 17]
[ThaliCore] Session.init(session:identifier:connected:notConnect,ed:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Advertiser: session connected Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:),
[ThaliCore] Session.session(_:peer:didChange:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D state: notConnected -> connecting
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:47 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:47 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
,[ThaliCore] Session.session(_:peer:didChange:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.startOutputStream(with:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [4, 5, 15, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EF040FDE-0D6B-4D8D-A867-F3E61402067D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:53:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 06:53:50 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [4, 5, 15, 16, 18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSo,cketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60787
[ThaliCore] Session.disconnect() peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}]'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","peerAvailable":false,"generation":null,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8E536049,-181F-4A81-B849-449127FF5604 error: max retries exceeded
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Connection could not be established","portNumber":null}'
2017-07-24 06:53:57 - DEBUG thaliMobi,leNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'Received peer avail,a,bility changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wit,h {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A8,1-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 06:53:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-24 06:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:57 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generat,ion":null,"portNumber":null,"recreated":true}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=,Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual ,socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,",portNumber":null,"recreated":true}'
2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] Adve,rtiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
,2017-07-24 06:53:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:15 [4, 5, 16, 18]
[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
ok 527 error should be null
,ok 528 error should be null
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] BrowserRelay.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [4, 5, 16]
,# setup
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 06:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
ok 543 should be equal
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
,ok 550 Entry exists
,ok 551 Size must be 1
,ok 552 Entry counter must be 2
,ok 553 Entry exists
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
ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-24 06:54:05 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:54:05 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-24 06:54:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 609 good enqueue
,ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
,ok 612 wrong arg type
,ok 613 wrong arg type
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
,2017-07-24 06:54:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:08 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 640 is an agent
2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does not throw
2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action ,Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-24 06:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-24 06:54:11 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-24 06:54:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-24 06:54:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-24 06:54:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-24 06:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-24 06:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-24 06:54:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-24 06:54:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 06:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-24 06:54:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
,ok 703 ecdh for local device cannot be null
,ok 704 milliseconds cannot be less than 0
,ok 705 milliseconds cannot be 0
,ok 706 milliseconds cannot be greater than one_day
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
,2017-07-24 06:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 743 bluetooth peer's notification has correct connection type
ok 744 tcp peer's notification has correct connection type
2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07,-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 06:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-24 06:54:30 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 06:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-24 06:54:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-24 06:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-24 06:54:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-24 06:54:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-24 06:54:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 06:54:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:35 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:35 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-24 06:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 06:54:38 - WARN thaliNotificationClient: 'peer is not available'
2017-07-24 06:54:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-24 06:54:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 06:54:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-24 06:54:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 06:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-24 06:54:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-24 06:54:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-24 06:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-24 06:54:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 06:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 06:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-24 06:54:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 06:54:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 06:54:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
ok 803 should be 204
,# teardown
,2017-07-24 06:54:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
,# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-24 06:54:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-24 06:54:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-24 06:54:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-24 06:54:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:54:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-24 06:54:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-24 06:54:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-24 06:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-24 06:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-24 06:54:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-24 06:54:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-24 06:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-24 06:54:56 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:54:57 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:54:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-24 06:54:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-24 06:55:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-24 06:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-24 06:55:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 06:55:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-24 06:55:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-24 06:55:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-24 06:55:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 06:55:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-24 06:55:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-24 06:55:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
,ok 865 same localDbName
,ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-24 06:55:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'listening 60923'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Browser.startListening
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:99E26CE2-0BAD-4BFD-95A2-9934C3008397
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Advertiser: session connected Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Advertiser: session connected Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8DF661A8-4296-4094-A555-B2F18A543288 state: notConnected -> connecting
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}]'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2C25BD08-82E6-4993-AE40-B3DCC8B04381 (syncValue: 4)'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] Session.init(sess,ion:identifier:connected:notConnected:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}]'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60927
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":60927}'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00404456-957A-4F5F-9043-36855CD19826 (syncValue: 5)'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [4, 5, 16, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 5, 16, 19, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DF661A8-4296-4094-A555-B2F18A543288 state: connecting -> connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [4, 5, 16, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [4, 5, 16, 19, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [4, 5, 16, 19, 20, 21, 22, 23]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [4, 5, 16, 19, 21, 22, 23]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 06:55:19 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
,[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [4, 5, 16, 19, 21, 23]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:00404456-957A-4F5F-9043-36855CD19826:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startO,utputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 5, 16, 19, 21, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [4, 5, 16, 19, 21, 23, 24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [4, 5, 16, 19, 21, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [4, 5, 16, 19, 21, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [4, 5, 16, 19, 21, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [4, 5, 16, 19, 21, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [4, 5, 16, 19, 21, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:34 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,7 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,33
[ThaliCore] VirtualSocket.deinit vsID:33 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withE,rror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered v,sID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 5
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Session.startOutputStream(with:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) c,lient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 37, 40, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 40, 41]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:00404456-957A-4F5F-9043-36855CD19826:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60953
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":60953}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8E536049-181F-4A81-B849-449127FF5604 (syncValue: 6)'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 42]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.startOutputStream(with:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,4 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 42, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.startOutputStream(with:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45]
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [4, 5, 16, 19, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [4, 5, 16, 19, 23, 24, 26, 27, 28, 29, 30, 31, 32, 35, 41, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [4, 5, 16, 19, 23, 24, 26, 28, 29, 30, 31, 32, 35, 41, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [4, 5, 16, 19, 23, 24, 26, 29, 30, 31, 32, 35, 41, 45, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [4, 5, 16, 19, 23, 24, 26, 29, 31, 32, 35, 41, 45, 48]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [4, 5, 16, 19, 23, 24, 26, 29, 31, 32, 35, 41, 45, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [4, 5, 16, 19, 23, 24, 26, 29, 31, 32, 35, 41, 45, 48]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.startOutputStream(with:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,0 [4, 5, 16, 19, 23, 24, 26, 29, 31, 32, 35, 41, 45, 48, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] AdvertiserRelay.didClos,eVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [4, 5, 16, 19, 23, 24, 26, 29, 31, 32, 35, 41, 45, 48]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:23 [4, 5, 16, 19, 24, 26, 29, 31, 32, 35, 41, 45, 48]
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:26 [4, 5, 16, 19, 24, 29, 31, 32, 35, 41, 45, 48]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
,[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:31 [4, 5, 16, 19, 24, 29, 32, 35, 41, 45, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [4, 5, 16, 19, 24, 29, 32, 41, 45, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [4, 5, 16, 19, 24, 29, 32, 41, 45, 48, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [4, 5, 16, 19, 24, 29, 32, 41, 48, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [4, 5, 16, 19, 24, 29, 32, 41, 51]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [4, 5, 16, 19, 24, 29, 32, 41]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [4, 5, 16, 19, 24, 29, 32, 41, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [4, 5, 16, 19, 24, 29, 32, 41, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [4, 5, 16, 19, 29, 32, 41, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [4, 5, 16, 19, 32, 41, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.deinit vsID:32 [4, 5, 16, 19, 41, 52, 53]
[ThaliCore] ,TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Advertise,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [4, 5, 16, 19, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [4, 5, 16, 19, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withErr,or:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 06:55:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,2017-07-24 06:55:23 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:53 [4, 5, 16, 19]
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60953
[ThaliCore] Session.disconnect() peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}]'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:55:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8E536049,-181F-4A81-B849-449127FF5604 error: max retries exceeded
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":"Connection could not be established","portNumber":null}'
2017-07-24 06:55:32 - DEBUG thaliMobi,leNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'Received peer avail,a,bility changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wit,h {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A8,1-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:99E26CE2-0BAD-4BFD-95A2-9934C3008397
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 06:55:32 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:55:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
[ThaliCore] AdvertiserManager,.stopAdvertising()
,2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 06:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
2017-07-24 06:55:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] VirtualSocket.deinit vsID:19 [4, 5, 16]
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
,ok 867 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [4, 5, 16, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [4, 5, 16]
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'listening 60967'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
,[ThaliCore] Browser.startListening
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [4, 5, 16, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [4, 5, 16]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Session.startOutputStream(with:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,6 [4, 5, 16, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [4, 5, 16]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25,BD08-82E6-4993-AE40-B3DCC8B04381:0
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E70E9642-D,542-4465-BF89-DFBB13C20E5E","generation":0}]'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}]'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8E536049-181F-4A81-B849-449127FF5604 (syncValue: 7)'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
[ThaliCore] Advertiser: session connected Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","generation":0}]'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60927
[ThaliCore] Session.disconnect() peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}]'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","generation":0}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:55:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:36 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.deinit peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] Session.startOutputStream(with:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [4, 5, 16, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
[ThaliCore] Session.startOutputStream(with:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [4, 5, 16, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [4, 5, 16, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:55:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 06:55:42 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 06:55:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E70E9642-D542-4465-BF89-DFBB13C20E5E (syncValue: 8)'
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,2017-07-24 06:55:42 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"gener,ation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60974
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":60974,}'
,2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2C25BD08-82E6-4993-AE40-B3DCC8B04381 (syncValue: 9)'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Advertiser: session connected Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631 state: notConnected -> connecting
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":"Peer is unavailable","portNumber":null}'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1 (syncValue: 10)'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0E,D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:55:45 - DEBUG thaliPeerPoolDefault: 'Got err  , Peer is unavailable'
2017-07-24 06:55:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24, 06:55:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2C25BD08-82E6-4993-AE40-B3DCC8B04381","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:),
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [4, 5, 16, 57, 59]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [4, 5, 16, 57]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [4, 5, 16, 57, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:46 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [4, 5, 16, 57]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
,[ThaliCore] Session.session(_:peer:didChange:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Session.startOutputStream(with:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,1 [4, 5, 16, 57, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [4, 5, 16, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Session.startOutputStream(with:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [4, 5, 16, 57, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60981
,2017-07-24 06:55:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":60981}'
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
,[ThaliCore] BrowserManager.disconnect peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [4, 5, 16, 57, 62, 63]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
,[ThaliCore] VirtualSocket.deinit vsID:63 [4, 5, 16, 57, 62]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [4, 5, 16, 57, 62, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:64 [4, 5, 16, 57, 62]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC
,2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E70E9642-D542-4465-BF89-DFBB13C20E5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:55:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 06:55:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:55:49 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:55:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 878 should throw
,# teardown
,# setup
,# Start and make sure it runs
,# teardown
,# setup
,# Make sure getTimeWhenRun is right after start
,ok 879 (unnamed assert)
,# teardown
,# setup
,# Make sure getTimeWhenRun is -1 after function is called
,ok 880 should be equal
# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 881 should be equal
ok 882 should be equal
ok 883 should throw
,# teardown
,# setup
,# Test TransientState
,ok 884 should throw
,ok 885 should throw
,ok 886 should be equal
,ok 887 should be equal
,ok 888 should be equal
,ok 889 should be equal
,ok 890 (unnamed assert)
,ok 891 (unnamed assert)
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
,2017-07-24 06:55:54 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 906 verify failed
,ok 907 constructor called once
,ok 908 constructor called with right args
,ok 909 match start arg
,ok 910 start called once
,ok 911 stop called once
,ok 912 stop after start
,# teardown
,# setup
,# One peer with _Local set equal to current seq
,2017-07-24 06:55:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:57 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:57 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 934 verify failed
,ok 935 constructor called once
,ok 936 constructor called with right args
,ok 937 match start arg
,ok 938 start called once
,ok 939 stop called once
,ok 940 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 948 verify failed
ok 949 constructor called once
,ok 950 constructor called with right args
ok 951 start before stop
ok 952 We got at least 3 calls to start
ok 953 at least 3
ok 954 default 1
,ok 955 1 run
,ok 956 default 2
,ok 957 2 run
,ok 958 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 959 start out null
,2017-07-24 06:56:00 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-07-24 06:56:00 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 961 still null
,ok 962 verify failed
ok 963 constructor called once
,ok 964 constructor called with right args
,ok 965 first start before first stop
,ok 966 first stop before second start
,ok 967 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-24 06:56:01 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 968 verify failed
,ok 969 constructor called once
,ok 970 constructor called with right args
,ok 971 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-24 06:56:02 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 (unnamed assert)
,ok 976 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-24 06:56:02 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 977 verify failed
,ok 978 constructor called once
,ok 979 constructor called with right args
,ok 980 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-24 06:56:03 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 981 verify failed
,ok 982 constructor called once
,ok 983 constructor called with right args
,ok 984 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 985 should be equal
ok 986 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-24 06:56:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:56:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 987 Got right error
,# teardown
,2017-07-24 06:56:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 988 Got socket hang up
,# teardown
,2017-07-24 06:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 989 Got 500 as expected
,# teardown
,2017-07-24 06:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-07-24 06:56:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-24 06:56:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,# teardown
,2017-07-24 06:56:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C044CC9B-,EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-24 06:56:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-24 06:56:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,044CC9B-EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C044CC9B-,EC99-48B6-9F7F-9DF7553FB01D/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-24 06:56:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-24 06:56:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-07-24 06:56:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1004 failed due to stop
,ok 1005 failed due to stop
,# teardown
,2017-07-24 06:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1006 should be equal
,# teardown
,2017-07-24 06:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-24 06:56:21 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1007 Expected bad seq error
,# teardown
,2017-07-24 06:56:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
,ok 1009 Timer was cancelled
,ok 1010 should be equal
,# teardown
,2017-07-24 06:56:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1011 One go and one blocked
,ok 1012 All blocked
,ok 1013 Still blocked
,ok 1014 should be equal
,# teardown
,2017-07-24 06:56:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1015 We waited long enough
,ok 1016 should be equal
,# teardown
,2017-07-24 06:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1017 Should have gotten same timer promise
,ok 1018 Still same timer promise
,ok 1019 We waited long enough
,ok 1020 should be equal
,# teardown
,2017-07-24 06:56:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-24 06:56:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1021 expressPouchDB was called once
,ok 1022 expressPouchDB was called with 2 arguments
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'listening 61053'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D798C383-7BCE-45BB-941F-B317278A7C96
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2FC1FD61-D37B-4C4C-AFBC-C0764870F00D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2FC1FD61-D37B-4C4C-AFBC-C0764870F00D
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1046 ThaliMobile.start was called once
,ok 1047 ThaliMobile.start was called with 3 arguments
,ok 1048 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2FC1FD61-D37B-4C4C-AFBC-C0764870F00D
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:56:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
,ok 1062 ThaliMobile.stop was called with 0 arguments
,ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1067 expressPouchDB was called once
,ok 1068 expressPouchDB was called with 2 arguments
,ok 1069 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1070 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1071 PouchDB was called once
,ok 1072 PouchDB was called with 1 arguments
,ok 1073 PouchDB was called with 'dbName' as 1-st argument
,ok 1074 ThaliSendNotificationBasedOnReplication was called once
,ok 1075 ThaliSendNotificationBasedOnReplication was called with 4 arguments
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 61055'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F15CBE86-7082-48A8-8A74-4484D1DEC69E
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E726A3FC-7240-4770-BFCC-871C1D89AA24", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E726A3FC-7240-4770-BFCC-871C1D89AA24
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1092 ThaliMobile.start was called once
,ok 1093 ThaliMobile.start was called with 3 arguments
,ok 1094 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1095 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1096 ThaliMobile.start was called with 'networkType' as 3-st argument
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
,2017-07-24 06:56:35 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E726A3FC-7240-4770-BFCC-871C1D89AA24
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'listening 61057'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:939449F6-61AB-4AFB-8878-2872F561D618
[ThaliCore] Browser.startListening
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1450B9D7-F3A6-4D85-BC43-B1B9D3BB8F91", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1450B9D7-F3A6-4D85-BC43-B1B9D3BB8F91
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1450B9D7-F3A6-4D85-BC43-B1B9D3BB8F91
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'listening 61059'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:56BEBC00-F6BA-4418-B18C-C34255A9E298
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB0CB0CE-86FD-449A-8199-3B137EB28831", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BB0CB0CE-86FD-449A-8199-3B137EB28831
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BB0CB0CE-86FD-449A-8199-3B137EB28831
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'listening 61061'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A99A756C-BCFC-4294-9079-A5144ACC9547
[ThaliCore] Browser.startListening
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8EAE0B2F-4293-4233-BE95-7B245785EC03", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8EAE0B2F-4293-4233-BE95-7B245785EC03
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-24 06:56:35 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8EAE0B2F-4293-4233-BE95-7B245785EC03
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# ssdp server and client should be restarted when wifi toggled
,2017-07-24 06:56:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when wifi toggled''
,# teardown
,# setup
,# ssdp server and client should be restarted when bssid changed
,2017-07-24 06:56:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted when bssid changed''
,# teardown
,# setup
,# ssdp server and client should be restarted only when advertising/listening is active
,2017-07-24 06:56:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'ssdp server and client should be restarted only when advertising/listening is active''
,# teardown
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 06:56:37 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached, handlers on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-24 06:56:37 - INFO Coor,dinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultD,irectory'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-07-24 06:56:37 - INFO Coordinate,dClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming ,connection cleans outgoing socket'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failu,re - new peer is ignored (MPCF)'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result,: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - should throw error when wrong remote db name is provided'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when wifi toggled'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted when bssid changed'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - ssdp server and client should be restarted only when advertising/listening is active'
,2017-07-24 06:56:37 - DEBUG CoordinatedClient: 'all unit tests succeeded, platformName: 'ios''
,2017-07-24 06:56:37 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-24 06:56:37 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-24 06:56:37 - DEBUG CoordinatedClient: 'test client succeed'
,2017-07-24 06:56:37 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-24 06:56:37 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
