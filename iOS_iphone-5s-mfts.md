#### Test 113351851c966256_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/BDB600F7-6045-43E7-9C78-7086235722B4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/BDB600F7-6045-43E7-9C78-7086235722B4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55736"
,(lldb)     command script import "/tmp/BDB600F7-6045-43E7-9C78-7086235722B4/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:37:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "765909E0-DEE4-40D6-9224-0D82C2DD4CEB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:765909E0-,DEE4-40D6-9224-0D82C2DD4CEB
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32624517-F813-4D67-A531-69E8B6377659
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB4B45D0-,4BE2-4C27-AB9C-2D8939BFC1BB
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D504B86B-2615-4142-8DEE-67A2B12B6B93", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D504B86B-2615-4142-8DEE-67A2B12B6B93
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D504B86B-2615-4142-8DEE-67A2B12B6B93:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D504B86B-2615-4142-8DEE-67A2B12B6B93", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 06:37:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.697982907295227
,2017-07-21 06:37:28 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-21 06:37:28 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D504B86B-2615-4142-8DEE-67A2B12B6B93:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D504B86B-2615-4142-8DEE-67A2B12B6B93", generation: 0)
,2017-07-21 06:37:32 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 06:37:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 06:37:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 06:37:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 06:37:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 06:37:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 06:37:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 06:37:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 06:37:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 06:37:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 06:37:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 06:37:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 06:37:36 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 06:37:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 06:37:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 06:37:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
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
,2017-07-21 06:38:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 06:38:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 06:38:07 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-21 06:38:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 06:38:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:54918E4A-5762-4877-B740-0AD8363884EB
,[ThaliCore] Browser.startListening
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CFB5E575-43C8-49EE-95D8-584F8A0178E8
[ThaliCore] Browser.startListening
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C5D042CF-EA86-4810-A601-E1AD2DE98F50", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C5D042CF-EA86-4810-A601-E1AD2DE98F50
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C5D042CF-EA86-4810-A601-E1AD2DE98F50
2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:24 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0684C358-2811-4DAC-AA8B-C5614EA6E543", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0684C358-2811-4DAC-AA8B-C5614EA6E543
2017-07-21 0,6:38:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0684C358-2811-4DAC-AA8B-C5614EA6E543", generation: 1)
[ThaliCore] A,dvertiser.startAdvertising with peerID:0684C358-2811-4DAC-AA8B-C5614EA6E543
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:26 - INFO thali,Mobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})',
2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:38:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0684C358-2811-4DAC-AA8B-C5614EA6E543
,[ThaliCore] Advertiser.stopAdvertising() peerID:0684C358-2811-4DAC-AA8B-C5614EA6E543
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5
2017-07-21 0,6:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F3156D84-403A-4A45-91A4-A15E10B5E173
[Thali,Core] Browser.startListening
2017-07-21 06:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:38:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9D1E844-1C42-470F-A71E-A77043BAEA21:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9D1E844-1C42-470F-A71E-A77043BAEA21", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FB2AB890-F1BF-4397-BF7D-A08733E010B3
2017-07-21 0,6:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72CDDB0B-4760-4EF6-BDA7-3C0D12FFAC88
[Thal,i,Core] Browser.startListening
2017-07-21 06:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:38:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:38:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
2017-07-21 06:38:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CBC5836A-0CD7-4B62-8474-DE0109A6D422","generation":0}'
2017-07-21 06:38:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CBC5836A-0CD7-4B62-8474-DE0109A6D422, (syncValue: cNNE4Bu9YHKa6Md67qFBZfsrfwDD6Pob)'
,2017-07-21 06:38:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30
[ThaliCore] Advertiser: session connected Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
2017-07-21 06:38:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA","generation":0}'
2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30 state: connecting -> connected
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56312
,2017-07-21 06:38:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cNNE4Bu9YHKa6Md67qFBZfsrfwDD6Pob","error":null,"portNumber":56312}'
,2017-07-21 06:38:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cNNE4Bu9YHKa6Md67qFBZfsrfwDD6Pob', error: 'null', listeningPort: '56312''
,2017-07-21 06:38:40 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 06:38:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:38:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FB2AB890-F1BF-4397-BF7D-A,08733E010B3
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56312
[ThaliCore] Session.disconnect() peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30
[ThaliCore] Advert,iserRelay.deinit
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F686267D-A694-4320-B2FC-1287833C0E7C
2017-07-21 0,6:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F
[Thal,iCore] Browser.startListening
2017-07-21 06:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:A7A8EE40-0C65-4C05-924B-AB3F71D4BD30
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
2017-07-21 06:38:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA","generation":0}'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA, (syncValue: 82cvDtGVS1UbdiypNR86UxL18tOJdJYH)'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9,A3AFA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","generation":0}'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","generation":0}'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
[ThaliCore] Advertiser: session connected Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
[ThaliCore] Session.startOutputStream(with:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9D6CB8CE,-C3F1-4704-B10F-2DA50F9A3AFA error: max retries exceeded
2017-07-21 06:38:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"82cvDtGVS1UbdiypNR86UxL18tOJdJYH","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:38:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '82cvDtGVS1UbdiypNR86UxL18tOJdJYH', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 06:38:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:38:54 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:38:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AF,A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:38:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:38:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:38:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06CC9300-6053-4EA1-8322-38AA391E12D9 (syncValue: aTJmHwS,RnXntub47BL3534GsfXTo0PUc)'
2017-07-21 06:38:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06CC9300-6053,-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:38:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56320
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aTJmHwSRnXntub47BL3534GsfXTo0PUc","error":null,"portNumber":56320}'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aTJmHwSRnXntub47BL3534GsfXTo0PUc', error: 'null', listeningPort: '56320''
,Connecting to the localhost:56320
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,Connected to the localhost:56320
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,# teardown
,2017-07-21 06:38:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:F686267D-A694-4320-B2FC-1287833C0E7C
2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:06CC9300-6053-4EA1-8322-38AA391E12D9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56320
[ThaliCore] Session.disconnect() p,eer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
,[ThaliCore] Session.deinit peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:68B8CE8A-2484-44B9-9163-E111100BA365
2017-07-21 0,6:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F03F61F2-0A23-48D5-9D1D-1B2D0F73AAB6
[ThaliCore] Browser.startListening
,2017-07-21 06:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","generation":0}'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06CC9300-6053-4EA1-8322-38AA391E12D9 (syncValue: W7Lfu1nN2Os1LtkaBZ36ol4MyNBa3yze)'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06,CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","generation":0}'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
2017-07-21 06:39:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","generation":0}'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","generation":0}'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
2017-07-21 06:39:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"W7Lfu1nN2Os1LtkaBZ36ol4MyNBa3yze","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'W7Lfu1nN2Os1LtkaBZ36ol4MyNBa3yze', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:39:02 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"06CC9300-6053-4EA1-8322-38AA391E12D9","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:39:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4E56564-627F-4CDE-8EE4-041EC9428CC9 (syncValue: 2u9z8bIIt4mXTrt2bxM03pl,s0QqVvYjy)'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4,E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 06:39:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[ThaliCore] Advertiser: session connected Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Advertiser: session connected Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D4E56564,-627F-4CDE-8EE4-041EC9428CC9 error: max retries exceeded
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2u9z8bIIt4mXTrt2bxM03pls0QqVvYjy","error":"Connection could not be established","portNumber":null}'
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2u9z8bIIt4mXTrt2bxM03pls0QqVvYjy', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF64E8D0-156A-46BC-86D9-00A60E9CC36C (syncValue: mvIRd5cRdcGIlwf7peS98vE3qdmFJH8Z)'
,2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[ThaliCore] Session.startOutputStream(with:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[ThaliCore] Session.startOutputStream(with:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
,[ThaliCore] Session.startOutputStream(with:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (2433 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,eamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
,[ThaliCore] Session.session(_:peer:didChange:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Session.startOutputStream(with:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56333
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Session.startOutputStream(with:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Session.startOutputStream(with:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 06:39:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mvIRd5cRdcGIlwf7peS98vE3qdmFJH8Z","error":null,"portNumber":56333}'
,2017-07-21 06:39:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mvIRd5cRdcGIlwf7peS98vE3qdmFJH8Z', error: 'null', listeningPort: '56333''
,Connecting to the localhost:56333
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,Connecting to the localhost:56333
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 7, 8, 9]
,Connecting to the localhost:56333
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [6, 7, 8, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [6, 7, 8, 9, 10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:56333
,Connected to the localhost:56333
,Connected to the localhost:56333
,ok 91 correct string length
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 06:39:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [7, 8, 9, 10, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 06:39:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [7, 8, 10, 11]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [7, 10, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didS,ocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:10
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:10 [7, 11]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,2017-07-21 06:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [11]
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:68B8CE8A-2484-44B9-9163-E111100BA365
,[ThaliCore] Session.session(_:peer:didChange:) peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Advert,iserRelay.deinit
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56333
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mvIRd5cRdcGIlwf7peS98vE3qdmFJH8Z","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:A928C67E-400B-4A0D-AE74-6DAE2631BABB
[ThaliCore] Session.deinit peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AD6E5E06-F813-4297-B2A5-EC52EB430D2A
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44610784-A0DB-4F9D-93DA-CC727176B199
,[ThaliCore] Browser.startListening
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
2017-07-21 06:39:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F8950B91-FC0C-4B52-9139-38BC77A5B47C, (syncValue: 12xm52gGXyKVEFodvZZ2S8GGZe0n0OKf)'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A,5B47C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
2017-07-21 06:39:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C5B3F0A4-79DB-4081-A9E4-DEF6058D0780","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09A4E702-E613-48D9-B9A2-3D033F105286","generation":0}'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
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
[ThaliCore] Session.disconnect() peer:F8,950B91-FC0C-4B52-9139-38BC77A5B47C:0
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
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12xm52gGXyKVEFodvZZ2S8GGZe0n0OKf","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '12xm52gGXyKVEFodvZZ2S8GGZe0n0OKf', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F8950B91-FC0C-4B52-9139-38BC77A5B47C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C5B3F0A4-79DB-4081-A9E4-DEF6058D0780 (syncValue: uj0qzNq,tL3m6Hux4dNhCEKyMug6zsYB7)'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C5B3F0A4-79DB,-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56354
,2017-07-21 06:39:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uj0qzNqtL3m6Hux4dNhCEKyMug6zsYB7","error":null,"portNumber":56354}'
,2017-07-21 06:39:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uj0qzNqtL3m6Hux4dNhCEKyMug6zsYB7', error: 'null', listeningPort: '56354''
,Connecting to the localhost:56354
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [11, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:56354
2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:39:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [11]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
,2017-07-21 06:39:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:AD6E5E06-F813-4297-B2A5-EC52EB430D2A
2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:,39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56354
[ThaliCore] Session.disconnect() p,eer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9B868A43-5BE8-46E6-9795-88F123A46132
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F090AAFD-5C96-46E7-B54B-705E443D5365
,[ThaliCore] Browser.startListening
2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
2017-07-21 06:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09A4E702-E613-48D9-B9A2-3D033F105286","generation":0}'
2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09A4E702-E613-48D9-B9A2-3D033F105286, (syncValue: nJEho3HhyhSq8ruxc5PcLP9YQDYbq8Gc)'
2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F1,05286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"C5B3F0A4-79DB-4081-A9E4-DEF6058D0780","generation":0}'
2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
2017-07-21 06:39:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
2017-07-21 06:39:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9A4E702-E613-48D9-B9A2-3D033F105286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9A4E702-E613-48D9-B9A2-3D033F105286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9A4E702-E613-48D9-B9A2-3D033F105286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09A4E702-E613-48D9-B9A2-3D033F105286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:09A4E702,-E613-48D9-B9A2-3D033F105286 error: max retries exceeded
2017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nJEho3HhyhSq8ruxc5PcLP9YQDYbq8Gc","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nJEho3HhyhSq8ruxc5PcLP9YQDYbq8Gc', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"09A4E702-E613-48D9-B9A2-3D033F105286","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"09A4E702-E613-48D9-B9A2-3D033F105286","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 345FB200-0861-4889-93A7-1CE465A33780 (syncValue: Lg1VXJN,MpO2q4EY3pPzCt7jW6Zr3abz4)'
2017-07-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:345FB200-0861,-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56370
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lg1VXJNMpO2q4EY3pPzCt7jW6Zr3abz4","error":null,"portNumber":56370}'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Lg1VXJNMpO2q4EY3pPzCt7jW6Zr3abz4', error: 'null', listeningPort: '56370''
,Connecting to the localhost:56370
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
,Connected to the localhost:56370
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [11, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [11]
,ok 102 got the same data back
,# teardown
,2017-07-21 06:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9B868A43-5BE8-46E6-9795-88F123A46132
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:345FB200-0861-4889-93A7-1CE465A33780
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56370
[ThaliCore] Session.disconnect() p,eer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26DA3355-FB46-4A07-BF46-4796E1CE8270
[ThaliCore] Browser.startListening
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:39:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E7DA81F-9EF9-447F-8F0A-8D715861C7B1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9E7DA81F-9EF9-447F-8F0A-8D715861C,7B1
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:39:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:39:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
2017-07-21 06:39:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}]'
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}]'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
,2017-07-21 06:39:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}]'
2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8EDCF724-AD07-4005-8DDC-A283D1F0F2FD","generation":0}'
2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9E7DA81F-9EF9-447F-8F0A-8D715861C7B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9E7DA81F-9EF9-447F-8F0A-8D715861C7B1", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3DB33481-9DE4-4D7C-9156-69DB440E3787:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
,2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3DB33481-9DE4-4D7C-9156-69DB440E3787","generation":0}]'
,2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3DB33481-9DE4-4D7C-9156-69DB440E3787","generation":0}'
2017-07-21 06:40:00 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9E7DA81F-9EF9-447F-8F0A-8D715861C7B1
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A1B31257-F234-449F-82AB-A15D6932D378
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7FE4DB3C-9B5D-4E9A-B7A4-AB85F529BE02", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7FE4DB3C-9B5D-4E9A-B7A4-AB85F529BE02
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7FE4DB3C-9B5D-4E9A-B7A4-AB85F529BE02
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 06:40:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
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
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3b2f6a51-fd9b-411e-8c62-5de3ecb03854 error: startListeningNotActive
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"edFgjKsvOAxlCO1qP1gv8wRNyOz5feUB","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3b2f6a51-fd9b-411e-8c62-5de3ecb03854","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3b2f6a51-fd9b-411e-8c62-5de3ecb03854","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF26718D-3BA3-48D1-AFA8-F0F05FB88947
,[ThaliCore] Browser.startListening
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yjyHmds4jrCICsqrOU6EAJ3MCv5FLMqf","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 06:40:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:561E273B-DC14-4738-A002-A15081552E89
[ThaliCore] Browser.startListening
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
,ok 138 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}]'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:ca655653-68b0-4f85-9c42-b811f8cbace5
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
,2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:021BF204-4241-4C41-8F59-593ED61743DF
2017-07-21 0,6:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:221F9872-C922-40B1-8C2B-9ECE3E0D28CC
[ThaliCore] Browser.startListening
2017-07-21 06:40:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 345FB200-0861-4889-93A7-1CE465A33780 (syncValue: c9gvtwv58OVV45FJK0nRKBNypnaG8s5i)'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6DBDADB5-5010-445C-87CD-6652E3BEFD76","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,5FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,45FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:40:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c9gvtwv58OVV45FJK0nRKBNypnaG8s5i","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:40:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c9gvtwv58OVV45FJK0nRKBNypnaG8s5i', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:40:16 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:40:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 06:40:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 06:40:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6DBDADB5-5010-445C-87CD-6652E3BEFD76 (syncValue: cgtvzb4tcFCBNhrXkCcsq8mJLu7j7us6)'
,2017-07-21 06:40:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56380
2017-07-21 06:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cgtvzb4tcFCBNhrXkCcsq8mJLu7j7us6",,"error":null,"portNumber":56380}'
2017-07-21 06:40:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cgtvzb4tcFCBNhrXkCcsq8mJLu7j7us6', error: 'null', listeningPort: '56380''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) found active relay
,2017-07-21 06:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Vp7YknGjZODjbFeVYxhaOMmfVaKcAnO1","error":null,"portNumber":56380}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) found active relay
,2017-07-21 06:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4DNcSJyVI8HSzxGs0aFa9kQBgJ14WCxg","error":null,"portNumber":56380}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [11, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:40:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:021BF204-4241-4C41-8F59-5,93ED61743DF
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56380
[ThaliCore] VirtualSocket.closeStr,eams() vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] Session.disconnect() peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:14 [11],
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-21 06:40:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 06:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 06:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 06:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56383'
ok 149 Should throw
,# teardown
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56385'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56388'
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
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 56392'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 56397'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56401'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56405'
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
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56409'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'listening 56413'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
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
2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 56465'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 56469'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56472'
,ok 196 port must be in range
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56473'
,ok 197 second start should return same port
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56475'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 06:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 56477
,ok 207 should be equal
,# teardown
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A
2017-07-21 0,6:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73
[ThaliCore] Browser.startListening
2017-07-21 06:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 06:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","generation":0}'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9EF037C-0FF4-439D-8907-DDAF0D922FDC (syncValue: zkvXRQOPxUrpIgCLg1RZbyUs49EquyIx)'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6DBDADB5-5010-445C-87CD-6652E3BEFD76","generation":0}'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
2017-07-21 06:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07","generation":0}'
2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","generation":0}'
2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5
[ThaliCore] Advertiser: session connected Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: notConnected -> connecting
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
[ThaliCore] Advertiser: session connected Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B9EF037C,-0FF4-439D-8907-DDAF0D922FDC error: max retries exceeded
2017-07-21 06:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zkvXRQOPxUrpIgCLg1RZbyUs49EquyIx","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zkvXRQOPxUrpIgCLg1RZbyUs49EquyIx', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:40:48 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 06:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9EF037C-0FF4-439D-8907-DDAF0D922FDC","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 06:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:40:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07 (syncValue: YM8GCCB,zj6gsGEwb6sGvNkIpqBkX5o65)'
,2017-07-21 06:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56491
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YM8GCCBzj6gsGEwb6sGvNkIpqBkX5o65","error":null,"portNumber":56491}'
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YM8GCCBzj6gsGEwb6sGvNkIpqBkX5o65', error: 'null', listeningPort: '56491''
,ok 210 should be equal
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B229F4CE-E556-41EA-9DF9-305580986B89 (syncValue: 490Vxnk4ykuTdNqqnKsRXMukZJRPPnRW)'
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56495
,2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"490Vxnk4ykuTdNqqnKsRXMukZJRPPnRW","error":null,"portNumber":56495}'
,2017-07-21 06:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '490Vxnk4ykuTdNqqnKsRXMukZJRPPnRW', error: 'null', listeningPort: '56495''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:40:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:97F9C3ED-F1BD-4C12-A7FD-B,7BF230EA03A
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56491
[ThaliCore] Session.disconnect() p,eer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AB595394-AD24-4AD2-964F-7F71E4BBADF,2
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:56495
[ThaliCore] Session.disconnect() peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:B229F4CE-E556-41EA-9DF9-305580986B89
2017-07-21 06:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[ThaliCore] Session.deinit peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
[ThaliCore] AdvertiserRelay.deinit
2017-07-21 06:40:56 - DEBUG thaliMobileNa,tiveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"490Vxnk4ykuTdNqqnKsRXMukZJRPPnRW","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:56 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B8,9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Multiple local http requests
,listening on 56497
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5
2017-07-21 0,6:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Browser.startListening
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
2017-07-21 06:40:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07","generation":0}'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07, (syncValue: gyvkB9hXph3hJzdUQLF8x1NeHNbqTXYG)'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3E,C7F07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
2017-07-21 06:40:57, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","generation":0}'
2017-07-21 06:40:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:57 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
2017-07-21 06:40:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
2017-07-21 06:40:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D8,0DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78
[ThaliCore] Advertiser: session connected Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D8,0DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:41:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gyvkB9hXph3hJzdUQLF8x1NeHNbqTXYG","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:41:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gyvkB9hXph3hJzdUQLF8x1NeHNbqTXYG', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:41:03 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:41:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 06:41:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:41:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B229F4CE-E556-41EA-9DF9-305580986B89 (syncValue: PLYQ1ako2NSvdBy3QKKgBTL,5nyAf27Ou)'
2017-07-21 06:41:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-30558,0986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:41:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:41:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,29F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,29F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,29F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57936B90-F736-49DF-90BA-74ED9D908149
[ThaliCore] Advertiser: session connected Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,29F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B229F4CE,-E556-41EA-9DF9-305580986B89 error: max retries exceeded
2017-07-21 06:41:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PLYQ1ako2NSvdBy3QKKgBTL5nyAf27Ou","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:41:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PLYQ1ako2NSvdBy3QKKgBTL5nyAf27Ou', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:41:14 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 06:41:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 06:41:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:41:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5689EEB6-FCF1-4CC7-9435-5FCCA56D8276 (syncValue: JwvXf6nxDXWFfZgIOCzueTXzh0f348mz)'
,2017-07-21 06:41:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:41:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:41:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57936B90-F736-49DF-90BA-74ED9D908149
,[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56519
,2017-07-21 06:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JwvXf6nxDXWFfZgIOCzueTXzh0f348mz","error":null,"portNumber":56519}'
,2017-07-21 06:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JwvXf6nxDXWFfZgIOCzueTXzh0f348mz', error: 'null', listeningPort: '56519''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 06:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DEBA3A8-6191-44CA-9535-55D68D86F143 (syncValue: roHFYLQJgWa49CrUtyZaTNH88LYodrWL)'
,2017-07-21 06:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:41:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56525
,2017-07-21 06:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"roHFYLQJgWa49CrUtyZaTNH88LYodrWL","error":null,"portNumber":56525}'
,2017-07-21 06:41:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'roHFYLQJgWa49CrUtyZaTNH88LYodrWL', error: 'null', listeningPort: '56525''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56519
[ThaliCore] Session.disconnect() p,eer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:1DEBA3A8-6191-44CA-9535-55D68D86F143
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56525
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,2017-07-21 06:41:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:57936B90-F736-49DF-90BA-74ED9D908149 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:57936B90-F736-49DF-90BA-74ED9D908149
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"roHFYLQJgWa49CrUtyZaTNH88LYodrWL","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] Session.deinit peer:57936B90-F736-49DF-90BA-74ED9D908149
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'listening 56529'
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
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'listening 56530'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB3E437D-0D39-4B6C-BB21-AF78CC565DDA
[ThaliCore] Browser.startListening
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 56531'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:4,1:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9", gen,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9
[ThaliCore] Advertiser.stopAdvertising() peerID:4D39E68D-7A6C-462D-97DF-FE7AFC2CC9D9
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'listening 56534'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,# error returned with bad router
,2017-07-21 06:41:26 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'listening 56535'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EEDC7E4B-2E6E-4933-906E-FD1D970DA91D
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F99AA677-FAFA-43D8-9B13-28D461AB885B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F99AA677-FAFA-43D8-9B13-28D461AB885B
2017-07-21 0,6:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F99AA677-FAFA-43D8-9B13-28D461AB885B
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 56538'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5BF6CE9A-9CA2-467C-8092-79CC330A01E7
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D75A9444-EADA-4B41-8380-FA7F5174F9BB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D75A9444-EADA-4B41-8380-FA7F5174F9BB
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D75A9444-EADA-4B41-8380-FA7F5174F9BB
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
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
,# all services are stopped when we call stop
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 56540'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:631DB5B3-F96A-4FE3-8E20-A979D6C7AC4A
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79F61999-938B-4B82-9E94-7315B72BB100", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:79F61999-938B-4B82-9E94-7315B72BB100
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79F61999-938B-4B82-9E94-7315B72BB100
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
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
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 06:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-21 06:41:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 06:41:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 06:41:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 06:41:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 06:41:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 06:41:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56543'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0ACFDA3-C246-46D0-9D96-262EA107B87C
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
ok 271 advertisingActive matches
,2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56544'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D18066E5-1933-463B-9FAD-4CFC71CD9F85", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D18066E5-1933-463B-9FAD-4CFC71CD9F85
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D18066E5-1933-463B-9FAD-4CFC71CD9F85
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56546'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'listening 56547'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A30D6478-BCCA-4864-BA71-A1CFA598DE40
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:848C26D1-5A2F-494E-B34B-2D176DF42AF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "848C26D1-5A2F-494E-B34B-2D176DF42AF7", generation: 0)
2017-07-21 06:41:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9226,9F1E-5F98-4DF6-91E3-B78B83019B41:0
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6,191-44CA-9535-55D68D86F143","generation":0}]'
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","generation":0}]'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","generation":0}'
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}]'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"848C26D1-5A2F-494E-B34B-2D176DF42AF7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 06:41:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 06:41:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'listening 56549'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:158AC3FC-E7FF-48C5-8A09-09E89B48A8FF
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "964F0DD7-1B92-4F4E-A048-636C8BB301EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:964F0DD7-1B92-4F4E-A048-636C8BB301EE
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DEBA3A8-6191-44CA-9535-55D68D86F143 (syncValue: IrmotoFzIbb3C3GQH1X5usBhNp1jpYe6)'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:38 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","generation":0}]'
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","generation":0}]'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:964F0DD7-1B92-4F4E-A048-636C8BB301EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "964F0DD7-1B92-4F4E-A048-636C8BB301EE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1D,EBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1D,EBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}]'
,2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
,2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:41:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1D,EBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IrmotoFzIbb3C3GQH1X5usBhNp1jpYe6","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IrmotoFzIbb3C3GQH1X5usBhNp1jpYe6', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 06:41:46 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:1DEBA3A8-6191-44CA-9535-55D68D86F143
2017-07-21 06:41:46 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5689EEB6-FCF1-4CC7-9435-5FCCA56D8276 (syncValue: vucf6ot1MuCB4PUDcfGqGeHoaqr0gCJA)'
,2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
2017-07-21 06:41:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}]'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
,2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,89EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,2017-07-21 06:41:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}]'
,2017-07-21 06:41:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","generation":0}'
,2017-07-21 06:41:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:41:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1DEBA3A8-6191-44CA-9535-55D68D86F143","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,89EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,89EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:56,89EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5689EEB6,-FCF1-4CC7-9435-5FCCA56D8276 error: max retries exceeded
2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vucf6ot1MuCB4PUDcfGqGeHoaqr0gCJA","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:41:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vucf6ot1MuCB4PUDcfGqGeHoaqr0gCJA', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:57 - DEBUG thaliMobil,eNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 06:41:57 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 82989E42-3B69-4258-A0E7-2C851A40B621 (syncValue: ZrvqhnPCdIgkHLqzgO6o3jknB5BafVyQ)'
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,2017-07-21 06:41:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 06:41:57 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56566
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZrvqhnPCdIgkHLqzgO6o3jknB5BafVyQ","error":null,"portNumber":56566}'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZrvqhnPCdIgkHLqzgO6o3jknB5BafVyQ', error: 'null', listeningPort: '56566''
,2017-07-21 06:42:00 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [11, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:00 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:00 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:964F0DD7-1B92-4F4E-A048-636C8BB301EE
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserManager.disconnect peer:82989E42-3B69-4258-A0E7-2C851A40B621
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.closeRelay() state:con,nected
[ThaliCore] VirtualSocket.deinit vsID:15 [11]
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56566
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] Session.disconnect,() peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
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
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:42:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 06:42:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-21, 06:42:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:42:05 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:42:05 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FD7FAF55-856C-48D4-87B6-76198D675423","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
,ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'listening 56568'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'listening 56569'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC110172-330C-4769-B308-A300CD789DE0
[ThaliCore] Browser.st,artListening
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'listening 56570'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B9AC2ECE-C29A-4626-AD39-DB9798BA4432", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:B9AC2ECE-C29A-4626-AD39-DB9798BA4432
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B9AC2ECE-C29A-4626-AD39-DB9798BA4432", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:B9AC2ECE-C29A-4626-AD39-DB9798BA4432
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B9AC2ECE-C29A-4626-AD39-DB9798BA4432
,[ThaliCore] Advertiser.stopAdvertising() peerID:B9AC2ECE-C29A-4626-AD39-DB9798BA4432
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'listening 56573'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 06:42:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 06:42:09 - DEBUG thaliMobileNativeWrapper: 'listening 56574'
ok 332 first call should succeed
ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 06:42:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
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
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"37ec6b97-3a72-4fa2-bef3-947b355d9869","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"37ec6b97-3a72-4fa2-bef3-947b355d9869","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5a37b44-a7d1-4895-8c7a-c9f7a697f227","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5a37b44-a7d1-4895-8c7a-c9f7a697f227","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c7900b2-05db-4293-b516-350b16bfd525","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c7900b2-05db-4293-b516-350b16bfd525","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bd160faa-1cd6-4046-8ba9-f26c7360f796","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"50e3245e-bc45-41f6-90d6-75b48f34d6f3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bd160faa-1cd6-4046-8ba9-f26c7360f796","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"50e3245e-bc45-41f6-90d6-75b48f34d6f3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93510a7b-cee9-4108-ae58-8059543fb9df","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"93510a7b-cee9-4108-ae58-8059543fb9df","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
,ok 378 error should be null
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
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b5fbeef-611b-455b-8a26-56a6268fe92e","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b5fbeef-611b-455b-8a26-56a6268fe92e","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be available
ok 388 should store correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7b5fbeef-611b-455b-8a26-56a6268fe92e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'listening 56575'
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4af8eb85-14b9-415b-a403-d8e65fbfef0d","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4af8eb85-14b9-415b-a403-d8e65fbfef0d","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4af8eb85-14b9-415b-a403-d8e65fbfef0d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'listening 56576'
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"661d1e18-600b-4ab8-abf8-a2ed44c11635","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"661d1e18-600b-4ab8-abf8-a2ed44c11635","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e1505bc4-8dc9-4d3d-92ce-6d79b8f22b64","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e1505bc4-8dc9-4d3d-92ce-6d79b8f22b64","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer, should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 56577'
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"de93236a-135f-4874-9e27-8dd583c0f38e","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9f040b13-bad4-46a9-95c4-dcfc6e68e928","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9f040b13-bad4-,46a9-95c4-dcfc6e68e928","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9f040b13-bad4-46a9-95c4-dcfc6e68e928","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9f040b13-bad4-46a9-95c4-dcfc6e68e928","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"de93236a-135f-4874-9e27-8dd583c0f38e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
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
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 56578'
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a6f3cdd-553d-49fa-87dd-1ca37a13b13d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9efbb238-c10f-4e25-99b1-e86a1760fd97","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1a6f3cdd-553d-49fa-87dd-1ca37a13b13d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9efbb238-c10f-4e25-99b1-e86a1760fd97","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
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
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14d6e035-4524-4a6c-91cb-e96c3c041229","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14d6e035-4524-4a6c-91cb-e96c3c041229","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14d6e035-4524-4a6c-91cb-e96c3c041229","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14d6e035-4524-4a6c-91cb-e96c3c041229","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14d6e035-4524-4a6c-91cb-e96c3c041229","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
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
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 56579'
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fbcb7818-c098-43a1-aa61-a5a5898085d1","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fbcb7818-c098-43a1-aa61-a5a5898085d1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 56580'
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c917110-67fb-4f1a-8a70-0df33e4d1c6a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:3c917110-67fb-4f1a-8a70-0df33e4d1c6a
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c917110-67fb-4f1a-8a70-0df33e4d1c6a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 06:42:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
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
,ok 496 error should be null
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
,ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'listening 56581'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:741261AE-A48E-4B0F-A83C-FEBCC7F0482E
,[ThaliCore] Browser.startListening
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"17d7bd4c-8e7d-44e8-9137-582bd5f1424d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3015fc39-f29e-42d8-8021-3b7877ccd3d6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"17d7bd4c-8e7d-44e8-9137-582bd5f1424d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3015fc39-f29e-42d8-8021-3b7877ccd3d6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'listening 56582'
2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"db84102d-4e84-40c3-b6cf-beb5b5b2a013","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52d318b4-26c6-4225-b266-2733d2112524","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"db84102d-4e84-40c3-b6cf-beb5b5b2a013","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52d318b4-26c6-4225-b266-2733d2112524","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
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
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'listening 56583'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "88123B38-04CB-418B-87E1-B5,C818C67E9F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:88123B38-04CB-418B-87E1-B5C818C67E9F
2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 522 error should be null
,ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] Browser.startListening
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
2017-07-21 06:42:27 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","generation":0}]'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","generation":0}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 69FD4252-E919-4997-B366-3BBAAB44C78C (syncValue: 0)'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
2017-07-21 06:42:27 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}]'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Advertiser: session connected Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] Advertiser: session connected Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599 state: notConnected -> connecting
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"83431272-1D7E-45BE-,9C4D-076F715AA398","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56586
2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":56586,}'
,2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 83431272-1D7E-45BE-9C4D-076F715AA398 (syncValue: 1)'
,2017-07-21 06:42:30 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [11, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:30 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:30 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] Session.session(_:peer:didChange:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [11, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
[ThaliCore] Session.startOutputStream(with:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [11, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56592
,2017-07-21 06:42:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":56592}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [11, 16, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:33 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:33 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-21 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83431272-1D7E-45BE-9C4D-076F715AA398","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:88123B38-04CB-418B-87E1-B5C818C67E9F
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [11, 17, 18, 19]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [11, 17, 19]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:17 [11, 19]
,ok 527 error should be null
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 528 error should be null
,# setup
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
ok 539 after start
2017-07-21 06:42:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 06:42:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 546 agent's destroy should be called
ok 547 agent's destroy should not be called again
ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
ok 550 Entry exists
,ok 551 Size must be 1
ok 552 Entry counter must be 2
ok 553 Entry exists
ok 554 Size must be 2
ok 555 Entry counter must be 1
ok 556 Entry exists
ok 557 Size must be 3
ok 558 Entry counter must be 2
ok 559 Entry exists
ok 560 Size must be 4
,ok 561 Entry 1_1 should not be found
ok 562 Entry 1_1 does not exist
ok 563 Size must be 3
,ok 564 Entry 1_2 should not be found
ok 565 Entry 1_2 does not exist
ok 566 Size must be 2
ok 567 should be equal
ok 568 Entry 2_1 should not be found
ok 569 Entry 2_2 should not be found
ok 570 Entry 2_1 does not exist
ok 571 Entry 2_2 does not exist
ok 572 Size must be 0
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
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 06:42:41 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:41 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 06:42:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
ok 601 is an agent
ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
ok 604 start action is killed
ok 605 killed action is still killed
ok 606 enqueued action when stopped is killed
ok 607 inQueue is empty
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
ok 612 wrong arg type
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
ok 624 first kill
ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
,ok 627 2nd good enqueue
,ok 628 1st action is in the pool
,ok 629 2nd action is in the pool
,ok 630 1st action is out of the pool
,ok 631 2st action is out of the pool
,ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 06:42:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 633 Got right error
ok 634 Start should not be called
ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 636 Got right error
ok 637 Start should not be called
ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 644 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
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
,ok 655 (unnamed assert)
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does not throw
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action, returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
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
,ok 689 must return null after successful call.
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
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 06:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 06:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 729 keys match
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
2017-07-21 06:43:12 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-21 06:43:13 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 06:43:13 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
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
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
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
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,# teardown
,2017-07-21 06:43:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
,# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 06:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 06:43:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
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
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
,# teardown
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 06:43:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 06:43:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
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
,2017-07-21 06:43:42 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:42 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-21 06:43:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 06:43:47 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:47 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 06:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 06:43:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 06:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 06:43:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-21 06:43:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 06:43:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'listening 56720'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Browser.startListening
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FE28E071-97B0-472F-81FD-46A648C78A9F
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
2017-07-21 06:44:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}]'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 2)'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B,-8743-D49D9B8F5AA6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:,notConnected:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
2017-07-21 06:44:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}]'
2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Advertiser,: session connected Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:830C9201-47E3-42BA-B571-27A4F2619A13 state: notConnected -> connecting
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Advertiser: session connected Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56723
2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":56723}'
,2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 3)'
,2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [11, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.session(_:peer:didChange:) peer:830C9201-47E3-42BA-B571-27A4F2619A13 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [11, 20, 21]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [11, 21]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [11, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [11, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [11, 22, 23]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C state: connecting -> connected
,2017-07-21 06:44:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [11, 22, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,5 [11, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [11, 22, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [11, 22, 23, 24, 25, 26, 27]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [11, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [11, 22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [11, 22, 23, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [11, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,32
[ThaliCore] VirtualSocket.deinit vsID:32 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:44:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [11, 22, 23, 24, 25, 26, 27, 29, 30, 31]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,29
[ThaliCore] VirtualSocket.deinit vsID:29 [11, 22, 23, 24, 25, 26, 27, 30, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56744
,2017-07-21 06:44:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":56744}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36, 37, 39]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [11, 22, 23, 24, 25, 26, 27, 30, 31, 35, 36, 37, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:24 [11, 22, ,23, 25, 26, 27, 30, 31, 35, 36, 37, 39, 40]
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:31 [11, 22, 23, 25, 26, 27, 30, 35, 36, 37, 39, 40]
[ThaliCore] VirtualSocket exited RunL,oop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [11, 22, 23, 25, 27, 30, 35, 36, 37, 39, 40]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [11, 22, 25, 27, 30, 35, 36, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [11, 22, 27, 30, 35, 36, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thali,Core] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [11, 22, 30, 35, 36, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [11, 22, 35, 36, 37, 39, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [11, 22, 35, 36, 37, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [11, 22, 35, 36, 37, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:39 [11, 22, 35, 36, 37, 40, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [11, 22, 35, 36, 37, 41, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [11, 22, 35, 36, 37, 42]
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [11, 22, 35, 36, 37, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [11, 22, 36, 37, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [11, 22, 37, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:37 [11, 22, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:42 [11, 22, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:44:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,2017-07-21 06:44:09 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FE28E071-97B0-472F-81FD-46A648C78A9F
,2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [11, 43]
,2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 867 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
,[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:43 [11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'listening 56751'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] Browser.startListening
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
2017-07-21 06:44:10 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}]'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","generation":0}'
2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}]'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 4)'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) found active relay
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":56744}'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 5)'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":56723}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [11, 44]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [11, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [11, 45]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDis,connectHandler
,2017-07-21 06:44:10 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:809FFB37-9982-4C97-A2BF-0029EAC1537F
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:45 [11]
,2017-07-21 06:44:10 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 6)'
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) found active relay
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":56744}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [11, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 7)'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":56723}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [11, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:46 [11, 47]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore,] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [11, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Session.startOutputStream(with:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [11, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:49
,[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:49 [11, 47, 48]
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 8)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":56723}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 9)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":56744}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [11, 47, 48, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
,[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:50 [11, 47, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [11, 47, 48, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [11, 47, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Advertiser: session connected Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
2017-07-21 06:44:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","generation":0}]'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","generation":0}'
2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","generation":0}]'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72682503-3E6C-4AF3-B364-3A3C1540F4CE (syncValue: 10)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] Advertiser: session connected Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB619F55-D26A-4861-90D3-606452E7D484 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:830C9201-47E3-4,2BA-B571-27A4F2619A13 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLoc,alhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
,[ThaliCore] Session.deinit peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC state: connecting -> connected
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56762
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":56762}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7 (syncValue: 11)'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [11, 47, 48, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Session.startOutputStream(with:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [11, 47, 48, 52, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [11, 47, 48, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:52
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Session.startOutputStream(with:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,4 [11, 47, 48, 52, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [11, 47, 48, 54]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [11, 47, 48, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:15 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:54 [11, 47, 48, 55]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [11, 47, 48]
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB619F55-D26A-4861-90D3-606452E7D484
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB619F55-D26A-4861-90D3-606452E7D484 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] Session.startOutputStream(with:) peer:AB619F55-D26A-4861-90D3-606452E7D484
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [11, 47, 48, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,56
[ThaliCore] VirtualSocket.deinit vsID:56 [11, 47, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRela,y.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB619F55-D26A-4861-90D3-606452E7D484
,[ThaliCore] Session.startOutputStream(with:) peer:AB619F55-D26A-4861-90D3-606452E7D484
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [11, 47, 48, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56771
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":56771}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 12)'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":56723}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5187EC00-26E2-4DBA-9E49-8E9F4B5E9607 (syncValue: 13)'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0) found active relay
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":56744}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [11, 47, 48, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [11, 47, 48, 57, 58, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
,[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [11, 47, 48, 57, 58]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepte,d socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [11, 47, 48, 57, 58, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
,[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [11, 47, 48, 57, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:58 [11, 47, 48, 57]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [11, 47, 48, 57, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [11, 47, 48, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [11, 47, 48]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56723
[ThaliCore] Session.disconnect() peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) relay removed
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}]'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:809FFB37-9982-4C97-A2BF-0029EAC1537F
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5187EC00-26E2-4DBA-9E49-8E9F4B5E9607","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [11, 47]
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 870 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 871 should throw
ok 872 should throw
ok 873 (unnamed assert)
ok 874 (unnamed assert)
ok 875 (unnamed assert)
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
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:27 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:29 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:29 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:30 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 948 verify failed
ok 949 constructor called once
,ok 950 constructor called with right args
ok 951 start before stop
ok 952 We got at least 3 calls to start
ok 953 at least 3
ok 954 default 1
ok 955 1 run
ok 956 default 2
ok 957 2 run
ok 958 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 959 start out null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 968 verify failed
,ok 969 constructor called once
,ok 970 constructor called with right args
,ok 971 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-21 06:44:33 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 (unnamed assert)
,ok 976 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-21 06:44:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 977 verify failed
,ok 978 constructor called once
,ok 979 constructor called with right args
,ok 980 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-21 06:44:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 987 Got right error
,# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 988 Got socket hang up
,# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 06:44:37 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 989 Got 500 as expected
,# teardown
,2017-07-21 06:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-07-21 06:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-21 06:44:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,# teardown
,2017-07-21 06:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C87A88CF-,718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 06:44:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-21 06:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/C,87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C87A88CF-,718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-21 06:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-21 06:44:45 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-07-21 06:44:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1004 failed due to stop
,ok 1005 failed due to stop
,# teardown
,2017-07-21 06:44:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1006 should be equal
,# teardown
,2017-07-21 06:44:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-21 06:44:49 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1007 Expected bad seq error
,# teardown
,2017-07-21 06:44:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
,ok 1009 Timer was cancelled
,ok 1010 should be equal
,# teardown
,2017-07-21 06:44:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1011 One go and one blocked
ok 1012 All blocked
,ok 1013 Still blocked
,ok 1014 should be equal
,# teardown
,2017-07-21 06:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1015 We waited long enough
,ok 1016 should be equal
,# teardown
,2017-07-21 06:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1017 Should have gotten same timer promise
,ok 1018 Still same timer promise
,ok 1019 We waited long enough
,ok 1020 should be equal
,# teardown
,2017-07-21 06:45:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-21 06:45:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'listening 56845'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE93644F-2A21-4D81-9CBA-58D615C3C208
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:01 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F7D3E4AF-E1B7-4F0A-BD87-EDFA8EE749DF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F7D3E4AF-E1B7-4F0A-BD87-EDFA8EE749DF
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F7D3E4AF-E1B7-4F0A-BD87-EDFA8EE749DF
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
,ok 1062 ThaliMobile.stop was called with 0 arguments
,ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 56847'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE65AFFB-D91C-43E4-ACB4-B1A4A6CE0E89
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5CB4A9D0-B24A-4FB2-A187-0857BF30DA9B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5CB4A9D0-B24A-4FB2-A187-0857BF30DA9B
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5CB4A9D0-B24A-4FB2-A187-0857BF30DA9B
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56849'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A2306913-71F1-4AFD-B733-A88A98830900
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "300B1C0A-BB6D-4924-8AE4-37281FDFBBAD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:300B1C0A-BB6D-4924-8AE4-37281FDFBBAD
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:300B1C0A-BB6D-4924-8AE4-37281FDFBBAD
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56851'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:575B733A-AF38-4651-9A76-863EC14F4D0C
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1DB3456D-56C0-40EF-963A-3EA04369A5A0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1DB3456D-56C0-40EF-963A-3EA04369A5A0
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1DB3456D-56C0-40EF-963A-3EA04369A5A0
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56853'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B3D168B4-9C44-4F13-877E-4AE16875AECD
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C919CCE-75EE-4222-9294-7E943E247589", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1C919CCE-75EE-4222-9294-7E943E247589
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1113 ThaliMobile.start was called once
ok 1114 ThaliMobile.start was called with 3 arguments
ok 1115 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 1116 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st arg,ument
ok 1117 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 1118 ThaliMobile.startListeningForAdvertisements was called once
,ok 1119 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 1120 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 1121 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1122 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1123 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1124 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1125 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1126 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1127 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1C919CCE-75EE-4222-9294-7E943E247589
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-21 06:45:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached, handlers on a single db change'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
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
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is c,alled'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
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
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
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
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
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
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
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
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-,B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,21 06:45:05 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 06:48:05 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-21 06:48:06 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/ww,w/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C87A88CF-718C-4E9F-B0A6-B6411B8436AB/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
,2017-07-21 06:48:06 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
