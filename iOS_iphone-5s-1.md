#### Test 113351851c966256_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/F9247C06-EB0E-4320-8990-483A7F30CB7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F9247C06-EB0E-4320-8990-483A7F30CB7C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851c966256/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55738"
,(lldb)     command script import "/tmp/F9247C06-EB0E-4320-8990-483A7F30CB7C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:37:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C84A3E36-7100-46F5-B26A-7478F9D8A0E9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C84A3E36-7100-46F5-B26A-7478F9D8A0E9
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1CDE75C5-9A4B-44C7-87D9-00C67E4BE4DB
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:61BAFA21-CC3D-47A5-8938-9F9D18DB5AB8
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort,:errorHandler:) Peer(uuid: "68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-21 06:37:39 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.420340001583099
,2017-07-21 06:37:39 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-21 06:37:39 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68FBE6C3-6D43-4FF4-BF8F-CCE6A281054D", generation: 0)
,2017-07-21 06:37:42 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 06:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 06:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 06:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 06:37:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 06:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 06:37:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 06:37:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 06:37:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 06:37:47 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 06:37:47 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 06:37:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 06:37:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
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
,2017-07-21 06:37:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
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
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 06:38:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:38:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 06:38:17 - DEBUG thaliMobileNa,tiveWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD6CF3BA-AAA8-4EB5-B2E9-1873ECA8D132
[ThaliCore] Browser.startListening
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 06:38:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:18 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26B62212-A53D-4D88-8C7E-30CE9E6E2120
[ThaliCore] Browser.startListening
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-2,1 06:38:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:19 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "33238194-9284-4FA3-8BD7-3E3711817D01", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:33238194-9284-4FA3-8BD7-3E3711817D01
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:33238194-9284-4FA3-8BD7-3E3711817D01
,2017-07-21 06:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:23 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ACCACC46-DFA5-4C0D-B32D-7F67708DE683", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ACCACC46-DFA5-4C0D-B32D-7F67708DE683
2017-07-21 0,6:38:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ACCACC46-DFA5-4C0D-B32D-7F67708DE683", generation: 1)
[ThaliCore] A,dvertiser.startAdvertising with peerID:ACCACC46-DFA5-4C0D-B32D-7F67708DE683
,2017-07-21 06:38:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ACCACC46-DFA5-4C0D-B32D-7F67708DE683
[ThaliCore] Advertiser.stopAdvertising() peerID:ACCACC46-DFA5-4C0D-B32D-7F67708DE683,
2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:38:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:38:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9D1E844-1C42-470F-A71E-A77043BAEA21", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D9D1E844-1C42-470F-A71E-A77043BAEA21
2017-07-21 06:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:30, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:D1F03DCA-3ED8-4213-B5AF-76882081289D
[ThaliCore] Browser.startListening
2017-07-21 06:38:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-21 06:38:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4D14FDE-8DE6-45E2-8E38-F7FC8DBAAB38", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A467C47C-CEFB-4C72-95CA-82A2A5CDEBC5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9D1E844-1C42-470F-A71E-A77043BAEA21:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9D1E844-1C42-470F-A71E-A77043BAEA21", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D9D1E844-1C42-470F-A71E-A77043BAEA21
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA
2017-07-21 0,6:38:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6BC80DF9-E102-4A96-B233-A23AE4892516
[Thali,Core] Browser.startListening
,2017-07-21 06:38:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CBC5836A-0CD7-4B62-8474-DE0109A6D422","generation":0}'
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CBC5836A-0CD7-4B62-8474-DE0109A6D422 (syncValue: lrrSHzHWGw1qXKK26grSw2ALhVpWwkgH)'
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FB2AB890-F1BF-4397-BF7D-A08733E010B3","generation":0}'
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CBC5836A-0CD7-4B62-8474-DE0109A6D422", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56154
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lrrSHzHWGw1qXKK26grSw2ALhVpWwkgH","error":null,"portN,umber":56154}'
2017-07-21 06:38:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lrrSHzHWGw1qXKK26grSw2ALhVpWwkgH', error: 'null', listeningPort: '56154''
,2017-07-21 06:38:42 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-21 06:38:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:9D6CB8CE-C3F1-4704-B10F-2DA50F9A3AFA
2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:38:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56154
,[ThaliCore] Session.disconnect() peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CBC5836A-0CD7-4B62-8474-DE0109A6D422:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:06CC9300-6053-4EA1-8322-38AA391E12D9
2017-07-21 0,6:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BCBC301-7F2A-49ED-B068-4B9DB22BCDA2
[ThaliCore] Browser.startListening
2017-07-21 06:38:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:38:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:38:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
2017-07-21 06:38:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FB2AB890-F1BF-4397-BF7D-A08733E010B3","generation":0}'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FB2AB890-F1BF-4397-BF7D-A08733E010B3, (syncValue: KcrchtssQmXRy8cQzwzaxNkUHMP7EC1A)'
2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E,010B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","generation":0}'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06CC9300-6053-4EA1-8322-38AA391E12D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","generation":0}'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:38:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57
[ThaliCore] Advertiser: session connected Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FB,2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,B2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FB2AB890-F1BF-4397-BF7D-A08733E010B3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:38:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KcrchtssQmXRy8cQzwzaxNkUHMP7EC1A","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:38:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KcrchtssQmXRy8cQzwzaxNkUHMP7EC1A', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:38:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"FB2AB890-F1BF-4397-BF7D-A08733E010B3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:38:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:38:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier,":"FB2AB890-F1BF-4397-BF7D-A08733E010B3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:38:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:38:,46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:38:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F686267D-A694-4320-B2FC-1287833C0E7C (syncValue: fOFks9gOOnDWDqpWHBMEEQF1Ny0OWLtl)'
2017,-07-21 06:38:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F6,86267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:38:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FB2AB890-F1BF-4397-BF7D-A08733E010B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57
,[ThaliCore] Session.session(_:peer:didChange:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57
,[ThaliCore] Session.startOutputStream(with:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 06:38:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56161
,2017-07-21 06:38:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fOFks9gOOnDWDqpWHBMEEQF1Ny0OWLtl","error":null,"portNumber":56161}'
,2017-07-21 06:38:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fOFks9gOOnDWDqpWHBMEEQF1Ny0OWLtl', error: 'null', listeningPort: '56161''
,Connecting to the localhost:56161
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,Connected to the localhost:56161
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:38:50 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F
[ThaliCore] Advertiser: session connected Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F
[ThaliCore] Session.startOutputStream(with:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 06:38:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 06:38:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:38:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:06CC9300-6053-4EA1-8322-3,8AA391E12D9
2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:F686267D-A694-4320-B2FC-1287833C0E7C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56161
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDE371EC-7EE6-4617-9155-91D8E302237F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EDE371EC-7EE6-4617-9155-91D8E302237F
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0374A4A2-CFD5-4A01-8EED-739A3BA2EE57 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "06CC9300-6053-4EA1-8322-38AA391E12D9", generation: 0)
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:38:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:38:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F8950B91-FC0C-4B52-9139-38BC77A5B47C
2017-07-21 0,6:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:66D68646-DFD9-4EE3-8CAD-05049315DE65
[Thal,i,Core] Browser.startListening
2017-07-21 06:38:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:38:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:38:59 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:EDE371EC-7EE6-4617-9155-91D8E302237F
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
2017-07-21 06:38:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","generation":0}'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F686267D-A694-4320-B2FC-1287833C0E7C, (syncValue: kfUXFykmxZAxgBKzW4fcln5kNbEB1oED)'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833,C0E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F686267D-A694-4320-B2FC-1287833C0E7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
,2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4E56564-627F-4CDE-8EE4-041EC9428CC9","generation":0}'
,2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:38:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
2017-07-21 06:39:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","generation":0}'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
2017-07-21 06:39:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","generation":0}'
2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F8950B91-FC0C-4B52-9139-38BC77A5B47C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F8950B91-FC0C-4B52-9139-38BC77A5B47C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D4E56564-627F-4CDE-8EE4-041EC9428CC9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D4E56564-627F-4CDE-8EE4-041EC9428CC9", generation: 0)
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
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kfUXFykmxZAxgBKzW4fcln5kNbEB1oED","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kfUXFykmxZAxgBKzW4fcln5kNbEB1oED', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F686267D-A694-4320-B2FC-1287833C0E7C","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 06:39:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68B8CE8A-2484-44B9-9163-E111100BA365 (syncValue: gzdKg1C,MuLsnoCbldngn0kbkdjHpdrhG)'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: ,0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F686267D-A694-4320-B2FC-1287833C0E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56178
2017-07-21 06:39:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gzdKg1CMuLsnoCbldngn0kbkdjHpdrhG",,"error":null,"portNumber":56178}'
2017-07-21 06:39:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gzdKg1CMuLsnoCbldngn0kbkdjHpdrhG', error: 'null', listeningPort: '56178''
,Connecting to the localhost:56178
Connecting to the localhost:56178
Connecting to the localhost:56178
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,Connected to the localhost:56178
Connected to the localhost:56178
,Connected to the localhost:56178
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 06:39:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 94 got the same data b,ack
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5, 6]
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,2017-07-21 06:39:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,06:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F8950B91-FC0C-4B52-9139-3,8BC77A5B47C
2017-07-21 06:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:68B8CE8A-2484-44B9-9163-E111100BA365
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56178
[ThaliCore] Session.disconnect() p,eer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:09A4E702-E613-48D9-B9A2-3D033F105286
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E2E75EAA-EE8C-4128-95FA-49BA0AE47618
,[ThaliCore] Browser.startListening
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
2017-07-21 06:39:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68B8CE8A-2484-44B9-9163-E111100BA365, (syncValue: wZqagBrMLn8E94Ur8kf2ACHbjWLtJAOk)'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100,BA365", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
2017-07-21 06:39:18, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","generation":0}'
2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
2017-07-21 06:39:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C5B3F0A4-79DB-4081-A9E4-DEF6058D0780","generation":0}'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
2017-07-21 06:39:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:39:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09A4E702-E613-48D9-B9A2-3D033F105286:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8B8CE8A-2484-44B9-9163-E111100BA365", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8B8CE8A-2484-44B9-9163-E111100BA365", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8B8CE8A-2484-44B9-9163-E111100BA365", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:68B8CE8A-2484-44B9-9163-E111100BA365:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:68B8CE8A,-2484-44B9-9163-E111100BA365 error: max retries exceeded
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wZqagBrMLn8E94Ur8kf2ACHbjWLtJAOk","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wZqagBrMLn8E94Ur8kf2ACHbjWLtJAOk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"68B8CE8A-2484-44B9-9163-E111100BA365","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:39:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF64E8D0-156A-46BC-86D9-00A60E9CC36C (syncValue: FChU2IP0RSkmkXSTqxUMjOC3ODe2ZqAF)'
,2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68B8CE8A-2484-44B9-9163-E111100BA365:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68B8CE8A-2484-44B9-9163-E111100BA365", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA
[ThaliCore] Advertiser: session connected Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA
[ThaliCore] Session.startOutputStream(with:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 06:39:34 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeSt,reams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 6]
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF64E8D0-156A-46BC-86D9-00A60E9CC36C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FChU2IP0RSkmkXSTqxUMjOC3ODe2ZqAF","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FChU2IP0RSkmkXSTqxUMjOC3ODe2ZqAF', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF64E8D0-156A-46BC-86D9-00A60E9CC36C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C5B3F0A4-79DB-4081-A9E4-DEF6058D0780 (syncValue: 415hVl17jK5VWtPzCtBiomIq3ZwOizCe)'
,2017-07-21 06:39:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 06:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CF64E8D0-156A-46BC-86D9-00A60E9CC36C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C5B3F0A4-79DB-4081-A9E4-DEF6058D0780", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56203
,2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"415hVl17jK5VWtPzCtBiomIq3ZwOizCe","error":null,"portNumber":56203}'
2017-07-21 06:39:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '415hVl17jK5VWtPzCtBiomIq3ZwOizCe', error: 'null', listeningPort: '56203''
,Connecting to the localhost:56203
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 6, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:56203
2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 06:39:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 6]
,2017-07-21 06:39:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:09A4E702-E613-48D9-B9A2-3D033F105286
2017-07-21 06:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-21 06:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Session.session(_:peer:didChange:) peer:AEBD38CB-E634-459B-A288-A86890FA81FA state: connected -> notConne,cted
[ThaliCore] Advertiser: session notConnected Peer(uuid: "09A4E702-E613-48D9-B9A2-3D033F105286", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore,] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AEBD38CB-E634-459B-A288-A86890FA81FA
[ThaliCore] BrowserManager.disconnect peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780
[ThaliCore] BrowserRelay.closeRelay() state:connected,
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56203
[ThaliCore] Session.disconnect() peer:C5B3F0A4-79DB-4081-A9E4-DEF6058D0780:0
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
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:AEBD38CB-E634-459B-A288-A86890FA81FA
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2967B371-2142-4D39-8DDA-E8E4121588B4
[ThaliCore] Browser.startListening
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:39:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 06:39:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","generation":0}'
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD6E5E06-F813-4297-B2A5-EC52EB430D2A (syncValue: UScuOLqxFcPRtswym6X8s5RkbEBFrsWm)'
,2017-07-21 06:39:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
,2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:39:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD6E5E06-F813-4297-B2A5-EC52EB430D2A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:39:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UScuOLqxFcPRtswym6X8s5RkbEBFrsWm","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:39:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UScuOLqxFcPRtswym6X8s5RkbEBFrsWm', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:39:51 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:39:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:39:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"AD6E5E06-F813-4297-B2A5-EC52EB430D2A","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 06:39:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:39:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 06:39:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 345FB200-0861-4889-93A7-1CE465A33780 (syncValue: ahlB0QV9shee2kMmbZMRLgN,xKE65zr0O)'
2017-07-21 06:39:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE46,5A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:39:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD6E5E06-F813-4297-B2A5-EC52EB430D2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56217
2017-07-21 06:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ahlB0QV9shee2kMmbZMRLgNxKE65zr0O",,"error":null,"portNumber":56217}'
2017-07-21 06:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ahlB0QV9shee2kMmbZMRLgNxKE65zr0O', error: 'null', listeningPort: '56217''
,Connecting to the localhost:56217
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
,Connected to the localhost:56217
,2017-07-21 06:39:53 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 06:39:53 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 6, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] Advertiser: session connected Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0F2FD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4BA51407-3670-434D-885C-F7F9855EAF16 state: notConnected -> connecting
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 6]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4BA51407-3670-434D-885C-F7F9855EAF16
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA51407-3670-434D-885C-F7F9855EAF16 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] Session.startOutputStream(with:) peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [1, 3, 6, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (44895 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received (15166 bytes):'
,2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 06:39:57 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[Tha,liCore] VirtualSocket.deinit vsID:10 [1, 3, 6]
,2017-07-21 06:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:8EDCF724-AD07-4005-8DDC-A283D1F0F2FD
2017-07-21 06:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:,39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:345FB200-0861-4889-93A7-1CE465A33780
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56217
[ThaliCore] Session.disconnect() p,eer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Session.session(_:peer:didChange:) peer:4BA51407-3670-434D-885C-F7F9855EAF16 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8EDCF724-AD07-4005-8DDC-A283D1F0,F2FD", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4BA51407-3670-434D-885C-F7F9855EAF16
[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:39:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 06:39:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C42450D3-8C2D-423C-B4F3-1F17D9EE03D2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C42450D3-8C2D-423C-B4F3-1F17D9EE03D2
2017-07-21 0,6:40:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:491DEF57-0B23-44D7-B348-9D6310678D7A
[ThaliCore] Browser.startListening
,2017-07-21 06:40:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:40:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9E7DA81F-9EF9-447F-8F0A-8D715861C7B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9E7DA81F-9EF9-447F-8F0A-8D715861C7B1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3DB33481-9DE4-4D7C-9156-69DB440E3787:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Advertiser.stopAdvertising() peerID:C42450D3-8C2D-423C-B4F3-1F17D9EE03D2
,2017-07-21 06:40:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:40:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:05 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 06:40:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:993EF80A-5BB8-43F0-85F3-47121C41D4F1
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "23773644-BFA3-4429-95D0-1BCD17979EF9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:23773644-BFA3-4429-95D0-1BCD17979EF9
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:23773644-BFA3-4429-95D0-1BCD17979EF9
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
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
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 06:40:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 06:40:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 06:40:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 06:40:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:482bd5b8-1795-4cc2-9b77-df172c9004de error: startListeningNotActive
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"W8zmcLFZ2rBIkATOELN4VFS1iLPmzdwC","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
,ok 132 listeningPort is null
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"482bd5b8-1795-4cc2-9b77-df172c9004de","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-,21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"482bd,5b8-1795-4cc2-9b77-df172c9004de","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E1C19662-ED70-4E5C-9814-0F91A0A2F111
[ThaliCore] Browser.startListening
2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Jwv1UJegUbQf5wuqRZ80ssjHcEj1N7Cj","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BC39987-815B-45FE-AF75-D59EFBB9A39E
,[ThaliCore] Browser.startListening
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:dc073d5b-44a9-46e8-893b-2f59ee1fc171
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B9EF037C-0FF4-439D-8907-DDAF0D922FDC
2017-07-21 0,6:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6EE8EC57-30D9-4CC3-A908-6AC23295A5F8
[ThaliCore] Browser.startListening
2017-07-21 06:40:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","generation":0}'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 345FB200-0861-4889-93A7-1CE465A33780 (syncValue: EAGLzajgpK4ocHrLfXdcd4B0a7FCac3I)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3DB33481-9DE4-4D7C-9156-69DB440E3787:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B868A43-5BE8-46E6-9795-88F123A46132","generation":0}'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3DB33481-9DE4-4D7C-9156-69DB440E3787","generation":0}'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6DBDADB5-5010-445C-87CD-6652E3BEFD76","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9EF037C-0FF4-439D-8907-DDAF0D922FDC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
2017-07-21 06:40:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","generation":0}'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:14 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,5FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,45FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,5FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,45FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3DB33481-9DE4-4D7C-9156-69DB440E3787:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3DB33481-9DE4-4D7C-9156-69DB440E3787", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,5FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,45FB200-0861-4889-93A7-1CE465A33780", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
2017-07-21 06:40:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B868A43-5BE8-46E6-9795-88F123A46132","generation":0}'
2017-07-21 06:40:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:23 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:345FB200-0861-4889-93A7-1CE465A33780:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,5FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "345FB200-0861-4889-93A7-1CE465A33780", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:345FB200,-0861-4889-93A7-1CE465A33780 error: max retries exceeded
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EAGLzajgpK4ocHrLfXdcd4B0a7FCac3I","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EAGLzajgpK4ocHrLfXdcd4B0a7FCac3I', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"345FB200-0861-4889-93A7-1CE465A33780","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6DBDADB5-5010-445C-87CD-6652E3BEFD76 (syncValue: OxvlSnB,oZVFbqSLj8n9yQF8TIvUyT7F2)'
2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:345FB200-0861-4889-93A7-1CE465A33780:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
[ThaliCore] Advertiser: session connected Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B868A43-5BE8-46E6-9795-88F123A46132:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B868A43-5BE8-46E6-9795-88F123A46132", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
,[ThaliCore] Session.session(_:peer:didChange:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56233
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96 state: connecting -> connected
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OxvlSnBoZVFbqSLj8n9yQF8TIvUyT7F2","error":null,"portNumber":56233}'
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OxvlSnBoZVFbqSLj8n9yQF8TIvUyT7F2', error: 'null', listeningPort: '56233''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
[ThaliCore] Session.startOutputStream(with:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 6, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 6, 11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) found active relay
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VAyiC4iqOtHz68G3KH7CNpgunso8TLmK","error":null,"portNumber":56233}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0) found active relay
,2017-07-21 06:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VrjbxmO3XsRJeWDNOWL8hBpbCTa3GQ79","error":null,"portNumber":56233}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-21 06:40:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B9EF037C-0FF4-439D-8907-DDAF0D922FDC
2017-07-21 06:40:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06,:,40:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] Virt,ualSocket.closeStreams() vsID:11
[ThaliCore] BrowserManager.disconnect peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56233
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 6, 12]
[ThaliCore] Session.session(_:peer:didChange:) peer:BFB441C5-7BEF-4892-8B40-F564CC686D96 state: connected -> notConnected
[ThaliCore] Advertiser: ses,sion notConnected Peer(uuid: "B9EF037C-0FF4-439D-8907-DDAF0D922FDC", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTC,PSession()
[ThaliCore] Session.disconnect() peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] Session.disconnect() peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 6]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BFB441C5-7BEF-4892-8B40-F564CC686D96
,[ThaliCore] Session.deinit peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
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
,2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-21 06:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
2017-07-21 06:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:40:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56237'
,ok 151 Should throw
,# teardown
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56239'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 06:40:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'listening 56242'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
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
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 56246'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
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
2017-07-21 06:40:32 - DEBUG createNativeListener: 'listening 56251'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56255'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56259'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 06:40:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'listening 56263'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-21 06:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-21 06:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 06:40:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:34 - DEBUG createNativeListener: 'listening 56267'
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
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
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
2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 56319'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'listening 56323'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-21 06:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 06:40:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
,ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56326'
ok 198 port must be in range
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56327'
,ok 199 second start should return same port
,# teardown
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 06:40:36 - DEBUG createNativeListener: 'listening 56329'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-21 06:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-21 06:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 06:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-21 06:40:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 56331
,ok 209 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07
2017-07-21 0,6:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB595394-AD24-4AD2-964F-7F71E4BBADF2
[ThaliCore] Browser.startListening
2017-07-21 06:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 06:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 021BF204-4241-4C41-8F59-593ED61743DF (syncValue: amSglarSNW28QnWyWwBXLZrmyPwDYHh4)'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "02,1BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6DBDADB5-5010-445C-87CD-6652E3BEFD76","generation":0}'
2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
2017-07-21 06:40:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","generation":0}'
2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:40:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 06:40:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","generation":0}'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
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
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,21BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:021BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6DBDADB5-5010-445C-87CD-6652E3BEFD76:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6DBDADB5-5010-445C-87CD-6652E3BEFD76", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:021BF204-4241-4C41-8F59-593ED61743DF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:02,1BF204-4241-4C41-8F59-593ED61743DF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,21BF204-4241-4C41-8F59-593ED61743DF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "021BF204-4241-4C41-8F59-593ED61743DF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:40:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"amSglarSNW28QnWyWwBXLZrmyPwDYHh4","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'amSglarSNW28QnWyWwBXLZrmyPwDYHh4', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:40:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 06:40:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"021BF204-4241-4C41-8F59-593ED61743DF","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 06:40:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 06:40:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A (syncValue: WEOJUSYosJGsJKkhr05OP3ilykNNnF8j)'
,2017-07-21 06:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:40:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:021BF204-4241-4C41-8F59-593ED61743DF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5
[ThaliCore] Advertiser: session connected Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73
[ThaliCore] Advertiser: session connected Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56347
,2017-07-21 06:40:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WEOJUSYosJGsJKkhr05OP3ilykNNnF8j","error":null,"portNumber":56347}'
2017-07-21 06:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'W,EOJUSYosJGsJKkhr05OP3ilykNNnF8j', error: 'null', listeningPort: '56347''
,ok 212 should be equal
2017-07-21 06:40:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B229F4CE-E556-41EA-9DF9-305580986B89 (syncValue: fZjsdMH1Uez2ijJ3NLcK32YS4MexEjYM)'
2017-07-21 06:40:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73
,[ThaliCore] Session.session(_:peer:didChange:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56351
2017-07-21 06:40:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fZjsdMH1Uez2ijJ3NLcK32YS4MexEjYM","error":null,"portN,umber":56351}'
,2017-07-21 06:40:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fZjsdMH1Uez2ijJ3NLcK32YS4MexEjYM', error: 'null', listeningPort: '56351''
,ok 213 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07
2017-07-21 06:40:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56347
[ThaliCore] Sess,ion.disconnect() peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:B229F4CE-E556-41EA-9DF9-305580986B89
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56351
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B229F4CE-E556-41EA-9DF9-305580986B89:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "B229F4CE-E556-41EA-9DF9-305580986B89", generation: 0)
,2017-07-21 06:40:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:21094AAD-E96C-406C-ABAF-25B50B148D73 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] Session.session(_:peer:didChange:) peer:BDB2C972-83F7-4156-841C-F88D47B911C5 state: connected -> notConnected
[ThaliCore] TCPClient.deinit
[Thal,iCore] Advertiser: session notConnected Peer(uuid: "D80DF37F-49FA-4AA6-BEE5-74D7A3EC7F07", generation: 0)
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:21094AAD-E96C-406C-ABAF-25B50B148D73
[ThaliCore] Advert,iserRelay.deinit
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fZjsdMH1Uez2ijJ3NLcK32YS4MexEjYM","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B229F4CE-E556-41EA-9DF9-305580986B89","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:40:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Multiple local http requests
,listening on 56353
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:40:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.deinit peer:21094AAD-E96C-406C-ABAF-25B50B148D73
,[ThaliCore] Session.deinit peer:B229F4CE-E556-41EA-9DF9-305580986B89:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1DEBA3A8-6191-44CA-9535-55D68D86F143
2017-07-21 0,6:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57936B90-F736-49DF-90BA-74ED9D908149
[ThaliCore] Browser.startListening
2017-07-21 06:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 06:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
2017-07-21 06:40:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","generation":0}'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A, (syncValue: eCA0JWVpvmWsGLnaeuEsu30RsoQhMM9G)'
2017-07-21 06:40:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230,EA03A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1DEBA3A8-6191-44CA-9535-55D68D86F143:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","generation":0}'
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 06:40:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78
[ThaliCore] Advertiser: session connected Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:97F9C3ED,-F1BD-4C12-A7FD-B7BF230EA03A error: max retries exceeded
2017-07-21 06:41:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eCA0JWVpvmWsGLnaeuEsu30RsoQhMM9G","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 06:41:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eCA0JWVpvmWsGLnaeuEsu30RsoQhMM9G', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 06:41:08 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 06:41:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5689EEB6-FCF1-4CC7-9435-5FCCA56D8276 (syncValue: 5oANJOH,MuXH4UWlriBuKQFRw4ES7gGlY)'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5689EEB6-FCF1,-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 06:41:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97F9C3ED-F1BD-4C12-A7FD-B7BF230EA03A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56371
,2017-07-21 06:41:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5oANJOHMuXH4UWlriBuKQFRw4ES7gGlY","error":null,"portNumber":56371}'
,2017-07-21 06:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5oANJOHMuXH4UWlriBuKQFRw4ES7gGlY', error: 'null', listeningPort: '56371''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-21 06:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4D260E1-1E5D-426D-8AB0-42B7621CD7F5 (syncValue: YVDgzpZjeXamK3Pfrgt8fXFQ5KMsprGp)'
,2017-07-21 06:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56377
,2017-07-21 06:41:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YVDgzpZjeXamK3Pfrgt8fXFQ5KMsprGp","error":null,"portNumber":56377}'
,2017-07-21 06:41:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YVDgzpZjeXamK3Pfrgt8fXFQ5KMsprGp', error: 'null', listeningPort: '56377''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Advertiser: session connected Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
,[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 06:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1DEBA3A8-6191-44CA-9535-55D68D86F143
2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56371
[ThaliCore] Session.disconnect() peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56377
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:06107CC2-63F0-4466-8497-8FD5EA8F0376 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4D260E1-1E5D-426D-8AB0-42B7621CD7F5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "B4D260E1-1E5D-426D-8AB0-42B7621CD7F5", generation: 0)
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
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YVDgzpZjeXamK3Pfrgt8fXFQ5KMsprGp","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4D260E1-1E5D-426D-8AB0-42B7621CD7F5","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AFF1BBF-CA5C-452B-A9E1-97A7293B6A78 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1DEBA3A8-6191-44CA-9535-55D68D86F143", generation: 0)
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Session.deinit peer:06107CC2-63F0-4466-8497-8FD5EA8F0376
[ThaliCore] Session.deinit peer:B4D260E1-1E5,D-426D-8AB0-42B7621CD7F5:0
[ThaliCore] BrowserRelay.deinit
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
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'listening 56381'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 56382'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F3E3727-602A-456A-A7D3-DA3DFD8C5C74
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 232 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisi,ngActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
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
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 56383'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C4D94E6-6CD7-4ABE-BE01-682B7C97045A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8C4D94E6-6CD7-4ABE-BE01-682B7C97045A
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C4D94E6-6CD7-4ABE-BE01-682B7C97045A", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:8C4D94E6-6CD7-4ABE-BE01-682B7C97045A
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8C4D94E6-6CD7-4ABE-BE01-682B7C97045A
,[ThaliCore] Advertiser.stopAdvertising() peerID:8C4D94E6-6CD7-4ABE-BE01-682B7C97045A
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
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
,2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'listening 56386'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActiv,e":false}'
2017-07-21 06:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
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
ok 243 specific error expected
,# teardown
,ok 244 must be stopped
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
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'listening 56387'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A860A2CF-322D-42D6-BAD7-1A3571132208
[ThaliCore] Browser.startListening
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79375B88-158F-4CB9-AD86-4011F9ACA507", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:79375B88-158F-4CB9-AD86-4011F9ACA507
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79375B88-158F-4CB9-AD86-4011F9ACA507
,2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
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
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 56390'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:24C95756-3D6C-4A94-A6D4-E47F5D230573
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "251A0CB8-619D-47A9-B29C-B9B6483D4C7D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:251A0CB8-619D-47A9-B29C-B9B6483D4C7D
2017-07-21 0,6:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:251A0CB8-619D-47A9-B29C-B9B6483D4C7D
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'listening 56392'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:573514A4-E3F8-4018-99FA-CB5E9F5FF7C4
[ThaliCore] Browser.st,artListening
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F56A7D3A-710C-467E-8F52-F91D8EFF84E0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F56A7D3A-710C-467E-8F52-F91D8EFF84E0
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F56A7D3A-710C-467E-8F52-F91D8EFF84E0
2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
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
,ok 252 must be stopped
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
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
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
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
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
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
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
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 06:41:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 262 must be stopped
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
,ok 263 must be stopped
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
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
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
,# make sure bad PSK connections fail
,2017-07-21 06:41:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,ok 267 must be stopped
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
,ok 268 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,ok 269 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56395'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C82FFFB1-6CDA-4A36-B71F-E5ED9258E101
,[ThaliCore] Browser.startListening
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56396'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1BABF32A-98AB-415E-AFD2-497D58625D5A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1BABF32A-98AB-415E-AFD2-497D58625D5A
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising,()
[ThaliCore] Advertiser.stopAdvertising() peerID:1BABF32A-98AB-415E-AFD2-497D58625D5A
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:41:33 - DEBUG thaliMobileNativeWrapper: 'listening 56398'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
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
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'listening 56399'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0769EC41-10AD-46DC-8156-B912486015B1
[ThaliCore] Browser.startListening
2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "848C26D1-5A2F-494E-B34B-2D176DF42AF7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:848C26D1-5A2F-494E-B34B-2D176DF42AF7
2017-07-21 06:41:34 - DEBUG thaliM,o,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,2017-07-21 06:41:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 279 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:92269F1E-5F98-4DF6-91E3-B78B83019B41:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
2017-07-21 06:41:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}]'
2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}'
,2017-07-21 06:41:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
2017-07-21 06:41:36 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 06:41:36 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5689EEB6-FCF1-4CC7-9435-5FCCA56D8276:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5689EEB6-FCF1-4CC7-9435-5FCCA56D8276", generation: 0)
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}]'
2017-07-21 06:41:36 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","generation":0}'
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:41:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5689EEB6-FCF1-4CC7-9435-5FCCA56D8276","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Browser,.browser(_:foundPeer:withDiscoveryInfo:) found peer:848C26D1-5A2F-494E-B34B-2D176DF42AF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "848C26D1-5A2F-494E-B34B-2D176DF42AF7", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:848C26D1-5A2F-494E-B34B-2D176DF42AF7
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 281 must be stopped
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
,ok 282 must be stopped
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
,ok 283 must be stopped
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
,ok 284 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 06:41:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'listening 56401'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE28369A-9858-4880-839F-FA3276B0D04B
[ThaliCore] Browser.startListening
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD7FAF55-856C-48D4-87B6-76198D675423
,2017-07-21 06:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 06:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:92269F1E-5F98-4DF6-91E3-B78B83019B41:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}]'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 353DCE66-3E1C-4FC6-910A-7333D0DEDF6E (syncValue: uWg3acDDibP3sFJ0C1D7JtkRhXjXFSg1)'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","generation":0}]'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:964F0DD7-1B92-4F4E-A048-636C8BB301EE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "964F0DD7-1B92-4F4E-A048-636C8BB301EE", generation: 0)
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","generation":0}]'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD7FAF55-856C-48D4-87B6-76198D675423:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:92269F1E-5F98-4DF6-91E3-B78B83019B41:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "92269F1E-5F98-4DF6-91E3-B78B83019B41", generation: 0)
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}]'
2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","generation":0}'
,2017-07-21 06:41:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 06:41:39 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"92269F1E-5F98-4DF6-91E3-B78B83019B41","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,3DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,53DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
2017-07-21 06:41:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}]'
2017-07-21 06:41:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","generation":0}'
,2017-07-21 06:41:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 06:41:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,3DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,53DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "353DCE66-3E1C-4FC6-910A-7333D0DEDF6E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uWg3acDDibP3sFJ0C1D7JtkRhXjXFSg1","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 06:41:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uWg3acDDibP3sFJ0C1D7JtkRhXjXFSg1', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:41:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 06:41:44 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 06:41:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"353DCE66-3E1C-4FC6-910A-7333D0DEDF6E","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E
2017-07-21 06:41:44 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
,2017-07-21 06:41:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 82989E42-3B69-4258-A0E7-2C851A40B621 (syncValue: TCo8XQFWSo1Uipz53NL8wEwmaOeH2ZPE)'
,2017-07-21 06:41:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:353DCE66-3E1C-4FC6-910A-7333D0DEDF6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "82989E42-3B69-4258-A0E7-2C851A40B621", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56407
2017-07-21 06:41:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TCo8XQFWSo1Uipz53NL8wEwmaOeH2ZPE",,"error":null,"portNumber":56407}'
2017-07-21 06:41:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TCo8XQFWSo1Uipz53NL8wEwmaOeH2ZPE', error: 'null', listeningPort: '56407''
,2017-07-21 06:41:46 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 6, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:41:47 - DEBUG testUtils: 'Got response data'
2017-07-21 06:41:47 - DEBUG testUtils: 'Got end'
,ok 285 response body should match testData
ok 286 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6
[ThaliCore] Advertiser: session connected Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6
,[ThaliCore] Session.session(_:peer:didChange:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6
[ThaliCore] Session.startOutputStream(with:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [1, 3, 6, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 6, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socke,t error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.d,idSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:956657AF-9654-4C83-928E-E4B8E61A74E6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD7FAF55-856C-48D4-87B6-76198D675423", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:956657AF-9654-4C83-928E-E4B8E61A74E6
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD7FAF55-856C-48D4-87B6-76198D675423
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:42:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 06:42:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:82989E42-3B69-4258-A0E7-2C851A40B621
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56407
,[ThaliCore] Session.disconnect() peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:82989E42-3B69-4258-A0E7-2C851A40B621:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:956657AF-9654-4C83-928E-E4B8E61A74E6
,# setup
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,2017-07-21 06:42:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 06:42:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 06:42:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 06:42:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 06:42:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 291 must be stopped
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
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-21 06:42:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82989E42-3B69-4258-A0E7-2C851A40B621","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"964F0DD7-1B92-4F4E-A048-636C8BB301EE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 294 error should be null
,ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 297 specific error should be returned
,# teardown
,ok 298 error should be null
ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'listening 56410'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error shoul,d be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'listening 56411'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A6B1A5C-CE76-4292-97AD-9F8ABC53BD3E
[ThaliCore] Browser.st,artListening
2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
ok 311 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'listening 56412'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "001AD9CE-E6CE-4489-BA51-F969B065A934", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:001AD9CE-E6CE-4489-BA51-F969B065A934
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "001AD9CE-E6CE-4489-BA51-F969B065A934", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:001AD9CE-E6CE-4489-BA51-F969B065A934
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:001AD9CE-E6CE-4489-BA51-F969B065A934
[ThaliCore] Advertiser.stopAdvertising() peerID:001AD9CE-E6CE-4489-BA51-F969B065A934
,2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'listening 56415'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 322 error should be null
ok 323 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 06:42:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
,ok 330 native router should be bad
,# teardown
,ok 331 error should be null
,ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 06:42:09 - DEBUG thaliMobileNativeWrapper: 'listening 56416'
,ok 334 first call should succeed
,ok 335 first call should succeed
,ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 06:42:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 06:42:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
,ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 06:42:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
,ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"36f9656e-2bd6-4ddc-93eb-2fe3632470c9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 346 should be calle,d once
ok 347 should not have been called more than once
,# teardown
,2017-07-21 06:42:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"36f9656e-2bd6-4ddc-93eb-2fe3632470c9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# can get the network status
,ok 351 network status should have certain non-empty properties
,# teardown
,ok 352 error should be null
,ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 355 we have not added peer to the cache yet
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"676298bc-b63c-4e08-aeff-835ef0bff171","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 356 peer should be available
ok 357 cache contains native peer
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"676298bc-b63c-4e08-aeff-835ef0bff171","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 358 peer should be unavailable
,ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f2d54284-7f24-4108-82ab-7234b6f978ca","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 364 peer should be available
ok 365 cache contains wifi peer
2017-07-21 06:42:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f2d54284-7f24-4108-82ab-7234b6f978ca","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 366 peer should be unavailable
,ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f4f62268-9b31-4c3f-82ad-adf5158f3a15","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 371 first peer is available
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd7bdf73-3803-459a-912d-786ffd893dcb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 372 second peer is available
,ok 373 first and second peers are different
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f4f62268-9b31-4c3f-82ad-adf5158f3a15","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dd7bdf73-3803-459a-912d-786ffd893dcb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
,ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cece3b04-c0a9-4a7f-96e1-82bb3937297f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 378 peer is available
,# teardown
,2017-07-21 06:42:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cece3b04-c0a9-4a7f-96e1-82bb3937297f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 06:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
,ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 06:42:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
,ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b85e0b0-be38-4ee5-ad4e-cca78f6ef299","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 388 peer should be ,available
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b85e0b0-be38-4ee5-ad4e-cca78f6ef299","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 389 peer should be ,available
ok 390 should store correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1b85e0b0-be38-4ee5-ad4e-cca78f6ef299","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
,ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'listening 56417'
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7a0fe061-e3bd-4ac5-8b7e-046a81b9368b","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7a0fe061-e3bd-4ac5-8b7e-046a81b9368b","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,# teardown
,2017-07-21 06:42:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7a0fe061-e3bd-4ac5-8b7e-046a81b9368b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 398 error should be null
,ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'listening 56418'
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ad42373-aff1-4fa9-af76-a824918b33bd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 401 discovered available peer
,ok 402 peer is available
,# teardown
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ad42373-aff1-4fa9-af76-a824918b33bd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
,ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3553d072-e514-4327-8f4a-63871154b946","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 406 peer should be ,available
2017-07-21 06:42:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3553d072-e514-4327-8f4a-63871154b946","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 407 peer, should be unavailable
ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 56419'
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4fc616ba-89b9-4e2b-bdd8-0da7aa77f6eb","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 412 first peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9bfb30a-c8c4-4215-9d61-affc8ca88ceb","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 413 second peer is expected to be available
2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9bfb30a-c8c4-,4215-9d61-affc8ca88ceb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 414 peer became unavailable
,ok 415 it was wifi peer
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9bfb30a-c8c4-4215-9d61-affc8ca88ceb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 we found peer again
,ok 417 it was wifi peer
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9bfb30a-c8c4-4215-9d61-affc8ca88ceb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 418 peer became unavailable
,ok 419 it was wifi peer
,# teardown
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4fc616ba-89b9-4e2b-bdd8-0da7aa77f6eb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 06:42:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'listening 56420'
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8b490c8b-ba4e-494e-a1e4-b6bae8db176a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 426 first peer is expected to be available
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"34047b90-2143-4fba-9bb4-142f2add6da3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 427 second peer is expected to be available
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8b490c8b-ba4e-494e-a1e4-b6bae8db176a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 428 peer became unavailable
,2017-07-21 06:42:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"34047b90-2143-4fba-9bb4-142f2add6da3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 06:42:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:42:18 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 06:42:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
,ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"262f949a-87ba-4ac6-ab2a-aad7c53dd185","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 439 peer discovered ,first time does not have new address
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"262f949a-87ba-4ac6-ab2a-aad7c53dd185","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 440 address has not been changed
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"262f949a-87ba-4ac6-ab2a-aad7c53dd185","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 441 new port handled correctly
,2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"262f949a-87ba-4ac6-ab2a-aad7c53dd185","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 442 new host handled, correctly
2017-07-21 06:42:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"262f949a-87ba-4ac6-ab2a-aad7c53dd185","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 443 new,AddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 06:42:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 450 NOT IMPLEMENTED # SKIP
,# teardown
,ok 451 error should be null
ok 452 error should be null
# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 06:42:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
,ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
,ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 06:42:21 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
,ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 464 contains expected properties
ok 465 the same ho,stAddress
,ok 466 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
,ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 470 contains expected properties
,ok 471 the same hostAddress
,ok 472 the same portNumber
,# teardown
,2017-07-21 06:42:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 56421'
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6b04d9bf-1254-4352-a18c-5524af493e7c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 476 Got specific error message
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6b04d9bf-1254-4352-a18c-5524af493e7c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'listening 56422'
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6f434b41-0c2d-4a1f-b3f1-aaca48b87ecb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:6f434b41-0c2d-4a1f-b3f1-aaca48b87ecb
,ok 480 native wrapper `disconnect` called once
,ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 06:42:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6f434b41-0c2d-4a1f-b3f1-aaca48b87ecb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 06:42:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
,ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
,ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 06:42:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 06:42:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
,ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 06:42:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'listening 56423'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:341396C8-2332-4FE5-A617-78337EFBAE25
,[ThaliCore] Browser.startListening
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58a6a499-fc69-484a-b6dc-ed5fee2345bf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e6f5bcdb-3902-49ee-9fad-8aebfa086222","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"58a6a499-fc69-484a-b6dc-ed5fee2345bf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e6f5bcdb-3902-49ee-9fad-8aebfa086222","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:42:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'listening 56424'
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d0071e90-7154-4fd0-ad9d-cfd7d0bb00d1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 1
,ok 515 2
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d5a4e74-cc7f-4f33-91b7-034a387cb7c2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d0071e90-7154-4fd0-ad9d-cfd7d0bb00d1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1d5a4e74-cc7f-4f33-91b7-034a387cb7c2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 06:42:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
,ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 06:42:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'listening 56425'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:83431272-1D7E-45BE-9C4D-076F715AA398
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F43D14D4-FBCA-4ED5-903E-91ED1EBB5599
,[ThaliCore] Browser.startListening
,2017-07-21 06:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 526 error should be null
,ok 527 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","generation":0}'
2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","generation":0}]'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","generation":0}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:42:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 88123B38-04CB-418B-87E1-B5C818C67E9F (syncValue: 0)'
,2017-07-21 06:42:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83431272-1D7E-45BE-9C4D-076F715AA398:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] Advertiser: session connected Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.session(_:peer:didChange:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "88123B38-04CB-418B-87E1-B5C818C67E9F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56428
2017-07-21 06:42:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":56428}'
,2017-07-21 06:42:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 69FD4252-E919-4997-B366-3BBAAB44C78C (syncValue: 1)'
2017-07-21 06:42:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:88123B38-04CB-418B-87E1-B5C818C67E9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 6, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:31 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:31 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
,[ThaliCore] Session.session(_:peer:didChange:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] Session.startOutputStream(with:) peer:1021915A-7DC2-4A2E-9966-C5EE31927BA1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 6, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 6, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "69FD4252-E919-4997-B366-3BBAAB44C78C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56434
,2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":56434}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:69FD4252-E919-4997-B366-3BBAAB44C78C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 6, 15, 16, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:42:34 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:34 - DEBUG testUtils: 'Got end'
,ok 528 received all uuids
,# teardown
,2017-07-21 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"88123B38-04CB-418B-87E1-B5C818C67E9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:42:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"69FD4252-E919-4997-B366-3BBAAB44C78C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:83431272-1D7E-45BE-9C4D-076F715AA398
2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 06:42:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-21 06:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[Th,aliCore] VirtualSocket.deinit vsID:18 [1, 3, 6, 15, 16, 17]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:42:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisco,nnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:17,
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [1, 3, 6, 15, 16]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 6, 15]
,ok 529 error should be null
,ok 530 error should be null
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 6]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
# setup
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 06:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 534 getPeerIdentifier
,ok 535 getConnectionType
,ok 536 getActionType
,ok 537 getActionState
,ok 538 getPskIdentity
,ok 539 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 540 initial state
,ok 541 after start
,2017-07-21 06:42:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 06:42:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 544 clean kill
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
,ok 549 agent's destroy should not be called again
,ok 550 agent is destroyed
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
ok 586 Size should be MAXSIZE
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
,ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
ok 597 good enqueue
,ok 598 Identity should match
,2017-07-21 06:42:41 - DEBUG testUtils: 'Got response data'
,2017-07-21 06:42:41 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-21 06:42:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 601 is an agent
ok 602 enqueue worked
ok 603 is an agent
ok 604 enqueue 2 worked
,ok 605 enqueue is not available when stopped
ok 606 start action is killed
ok 607 killed action is still killed
ok 608 enqueued action when stopped is killed
ok 609 inQueue is empty
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
,ok 614 wrong arg type
,ok 615 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 616 good enqueue
ok 617 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 618 good enqueue
,ok 619 2nd good enqueue
,ok 620 we are in the pool
,ok 621 We are out of the pool
,ok 622 Action was killed
,ok 623 The original kill was called too
,ok 624 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 625 good enqueue
ok 626 first kill
ok 627 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 628 1st good enqueue
ok 629 2nd good enqueue
ok 630 1st action is in the pool
ok 631 2nd action is in the pool
ok 632 1st action is out of the pool
ok 633 2st action is out of the pool
,ok 634 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 06:42:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
ok 636 Start should not be called
ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 638 Got right error
,ok 639 Start should not be called
,ok 640 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 641 Got null
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 642 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 644 Got Null
ok 645 Got another null
2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 646 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
,2017-07-21 06:42:47 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
,ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 651 should have gotten null
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 652 Should have stopped nicely
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 653 Still looking for null
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 06:42:48 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 654 Yup, another null
,ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 656 Null 1
,ok 657 (unnamed assert)
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 658 is an agent
,ok 659 Null 3
,ok 660 Replication not yet called
,ok 661 Notification 2 not yet called
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 662 is an agent
,ok 663 Notification went first
,ok 664 Notification 2 not called yet
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 665 is an agent
,ok 666 Notification finished
,ok 667 Replication finished
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 First does not throw
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 670 is an agent
,ok 671 Second does not throw
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 06:42:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 first ok
,2017-07-21 06:42:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 second ok
,ok 676 third ok
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
,ok 677 peerIdentifier should match
,ok 678 generation should match
,ok 679 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 680 good beacon
,ok 681 good preAmble
,ok 682 public keys match!
,ok 683 must return null after successful call
,ok 684 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 06:42:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 06:42:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 06:42:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
,ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 06:42:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
,ok 688 correct error message
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
,ok 693 Start after killed
,# teardown
,2017-07-21 06:42:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
,ok 695 must return null after successful kill
,# teardown
,2017-07-21 06:42:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
ok 697 must return null after successful kill
,# teardown
,2017-07-21 06:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-21 06:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 06:43:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 700 Should be NETWORK_PROBLEM caused closing server socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-21 06:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 704 publicKeysToNotify cannot be null
,ok 705 ecdh for local device cannot be null
ok 706 milliseconds cannot be less than 0
ok 707 milliseconds cannot be 0
ok 708 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 709 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 710 should be equal
,ok 711 should be equal
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
,2017-07-21 06:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 721 should be equal
,ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 723 right number of calls to address book
,ok 724 good preAmble
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
ok 734 keys match
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
,2017-07-21 06:43:12 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 06:43:12 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
,2017-07-21 06:43:13 - WARN thaliNotificationClient: 'peer is not available'
,ok 748 notification peer dictionary does not contain any peers
,2017-07-21 06:43:13 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-21 06:43:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
,ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-21 06:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-21 06:43:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-21 06:43:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-21 06:43:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 06:43:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 06:43:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-21 06:43:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 06:43:21 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 06:43:21 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
,# teardown
,2017-07-21 06:43:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
ok 773 peer state should be RESOLVED
,# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 06:43:22 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 774 First action failed
,ok 775 second action killed
# teardown
,2017-07-21 06:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
,ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-21 06:43:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 06:43:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-21 06:43:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 06:43:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 06:43:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-21 06:43:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 06:43:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 06:43:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
,ok 807 should be 204
,# teardown
,2017-07-21 06:43:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
,# teardown
,2017-07-21 06:43:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
,ok 810 not equal connection type
,ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 06:43:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-21 06:43:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 814 First start and on called correctly
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
,2017-07-21 06:43:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 823 listener has been set
,ok 824 peer dictionary has expected number of entries
,ok 825 Dictionary and pool have same action
,ok 826 ads match
,ok 827 PouchDB matches
,ok 828 DB Names match
,ok 829 public keys match
,ok 830 peer dictionary has expected number of entries
,ok 831 Dictionary and pool have same action
,ok 832 ads match
,ok 833 PouchDB matches
,ok 834 DB Names match
,ok 835 public keys match
,2017-07-21 06:43:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 06:43:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 06:43:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:43:36 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 06:43:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 849 right error
,# teardown
,2017-07-21 06:43:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 06:43:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 06:43:37 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-21 06:43:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 06:43:38 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 06:43:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 06:43:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-21 06:43:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 06:43:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-21 06:43:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 06:43:42 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:42 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 06:43:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 06:43:47 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:47 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
,ok 857 All tests passed!
,# teardown
,2017-07-21 06:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 06:43:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 06:43:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-21 06:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 06:43:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 06:43:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 06:43:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 862 action should be killed
ok 863 Error should be timed out
,# teardown
,2017-07-21 06:43:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-21 06:43:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
ok 866 Same pouchdB
ok 867 same localDbName
ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 06:43:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'listening 56561'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68E27EF3-CB0B-4051-8D0D-E00E7665799C
[ThaliCore] Browser.startListening
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607
,2017-07-21 06:44:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}]'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 2)'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
,2017-07-21 06:44:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56564
,2017-07-21 06:44:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":56564}'
,2017-07-21 06:44:02 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 3)'
,2017-07-21 06:44:02 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE,28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 6, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 6, 19, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,2017-07-21 06:44:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 6, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Advertiser: session connected Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Advertiser: session connected Peer(uuid: "5187EC00-26E2-4DBA-9E49-8E9F4B5E9607", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:830C9201-47E3-42BA-B571-27A4F2619A13 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 3, 6, 19, 20, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56571
,2017-07-21 06:44:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":56571}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 3, 6, 19, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 6, 19, 20, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 6, 19, 20, 21, 22, 24]
,2017-07-21 06:44:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 06:44:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 6, 19, 20, 21, 22, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 3, 6, 19, 20, 21, 22, 24]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 6, 19, 20, 21, 22, 24, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 6, 19, 20, 21, 22, 26]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 6, 19, 20, 21, 22, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 6, 19, 20, 21, 22, 27]
,2017-07-21 06:44:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 6, 19, 20, 21, 22, 27, 28]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,2017-07-21 06:44:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.session(_:peer:didChange:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:830C9201-47E3-42BA-B571-27A4F2619A13 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 32]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 32, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
,[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 34]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 34, 35]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:37
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,0 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 6, 19, 20, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39]
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 6, 19, 21, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 6, 19, 22, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 6, 19, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 3, 6, 19, 27, 28, 29, 30, 31, 35, 36, 37, 38, 39, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 6, 19, 28, 29, 30, 31, 35, 36, 37, 38, 39, 41]
,2017-07-21 06:44:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 6, 19, 28, 29, 30, 31, 35, 36, 37, 38, 39, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 6, 19, 28, 29, 30, 31, 35, 36, 37, 38, 39, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 6, 19, 28, 29, 30, 31, 35, 37, 38, 39, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
[ThaliCore] Session.startOutputStream(with:) peer:830C9201-47E3-42BA-B571-27A4F2619A13
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 6, 19, 28, 29, 30, 31, 35, 37, 38, 39, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 3, 6, 19, 28, 29, 30, 31, 35, 37, 38, 41, 42, 43, 44]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDiscon,nect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 6, 19, 28, 29, 30, 31, 35, 37, 38, 41, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 6, 19, 28, 29, 30, 31, 37, 38, 41, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 6, 19, 28, 29, 30, 31, 37, 41, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 6, 19, 28, 29, 30, 31, 37, 41, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 6, 19, 28, 29, 30, 31, 37, 43, 44, 45]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 6, 19, 28, 30, 31, 37, 43, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 6, 19, 28, 31, 37, 43, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 6, 19, 28, 37, 43, 44, 45]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 6, 19, 28, 37, 44, 45]
,2017-07-21 06:44:09 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 06:44:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5187EC00-26E2-4DBA-9E49-8E9F4B5E9607
2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 06:44:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 06:44:09 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:44:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAd,vertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:44:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:44
[ThaliCore] VirtualSocket.closeS,treams() vsID:44
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:45
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 6, 19, 28, 37, 45]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 6, 19, 28, 37]
,ok 869 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'listening 56595'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB619F55-D26A-4861-90D3-606452E7D484
,[ThaliCore] Browser.startListening
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 6, 19, 28, 37, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 6, 19, 28, 37]
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7
,2017-07-21 06:44:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [1, 3, 6, 19, 28, 37, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 6, 19, 28, 37]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}]'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 4)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":56571}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 5)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":56564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 6, 19, 28, 37, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 6, 19, 28, 37, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 6, 19, 28, 37, 49]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [1, 3, 6, 19, 28, 37]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 6)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":56564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 6, 19, 28, 37, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 6, 19, 28, 37]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 7)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) found active relay
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":56571}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 6, 19, 28, 37, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vs,ID:51 [1, 3, 6, 19, 28, 37]
,2017-07-21 06:44:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","generation":0}]'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72682503-3E6C-4AF3-B364-3A3C1540F4CE (syncValue: 8)'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 6, 19, 28, 37, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error, in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 6, 19, 28, 37]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","generation":0}]'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","generation":0}'
,2017-07-21 06:44:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 06:44:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "72682503-3E6C-4AF3-B364-3A3C1540F4CE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56605
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":56605}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 809FFB37-9982-4C97-A2BF-0029EAC1537F (syncValue: 9)'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 6, 19, 28, 37, 53]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56571
[ThaliCore] Session.disconnect() peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 6, 19, 28, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72682503-3E6C-4AF3-B364-3A3C1540F4CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 6, 19, 28, 37, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:14 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-21 06:44:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
,2017-07-21 06:44:14 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 870 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 6, 19, 28, 37]
,[ThaliCore] Session.session(_:peer:didChange:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] Advertiser: session connected Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 6, 19, 28, 37, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Advertiser: session connected Peer(uuid: "B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC state: notConnected -> connecting
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=35 "Resource temporarily unavailable" UserInfo={NSLocalizedDescription=Resource temporarily unavailable, NSLocalizedFailu,reReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 6, 19, 28, 37]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FE28E071-97B0-472F-81FD-46A648C78A9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
2017-07-21 06:44:16 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}]'
2017-07-21 06:44:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","generation":0}'
,2017-07-21 06:44:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 06:44:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 06:44:16 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "809FFB37-9982-4C97-A2BF-0029EAC1537F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56611
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":56611}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 10)'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":56564}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 11)'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FE28E071-97B0-472F-81FD-46A648C78A9F (syncValue: 12)'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE28E071-97B0-472F-81FD-46A648C78A9F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 06:44:17 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 3, 6, 19, 28, 37, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 6, 19, 28, 37, 56, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FE28E071-97B0-472F-81FD-46A648C78A9F","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:FE28E071-97B0-472F-81FD-46A648C78A9F
,[ThaliCore] BrowserManager.disconnect peer:FE28E071-97B0-472F-81FD-46A648C78A9F
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 6, 19, 28, 37, 56]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserR,elay.didSocketDisconnectHandler
,2017-07-21 06:44:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 6, 19, 28, 37]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Session.startOutputStream(with:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 6, 19, 28, 37, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:809FFB37-9982-4C97-A2BF-0029EAC1537F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 3, 6, 19, 28, 37, 58, 59]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [1, 3, 6, 19, 28, 37, 58, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [1, 3, 6, 19, 28, 37, 58, 59]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] Session.session(_:peer:didChange:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] Session.startOutputStream(with:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 6, 19, 28, 37, 58, 59, 61]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 6, 19, 28, 37, 59, 61]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
[ThaliCore] Session.startOutputStream(with:) peer:53FC0754-967F-4DFA-92BF-B582F6BBCA26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 6, 19, 28, 37, 59, 61, 62]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
,[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
[ThaliCore] Session.startOutputStream(with:) peer:ACBCE97F-51A6-414B-B118-5F9CA3C998BC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [1, 3, 6, 19, 28, 37, 59, 61, 62, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [1, 3, 6, 19, 28, 37, 59, 61, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] Session.startOutputStream(with:) peer:23B7BBA8-16B5-423D-BF5D-94DBC2506C9D
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountere,d vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [1, 3, 6, 19, 28, 37, 59, 61, 62, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 3, 6, 19, 28, 37, 59, 62, 64]
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 06:44:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 871 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 6, 19, 28, 37, 62, 64]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] Session.startOutputStream(with:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [1, 3, 6, 19, 28, 37, 62, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [1, 3, 6, 19, 28, 37, 62, 64]
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 439F642B-C473-4E6B-8743-D49D9B8F5AA6 (syncValue: 13)'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0) found active relay
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":56564}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [1, 3, 6, 19, 28, 37, 62, 64, 66]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocket,StreamsHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [1, 3, 6, 19, 28, 37, 62, 66]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:66 [1,, 3, 6, 19, 28, 37, 62]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 06:44:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "83431272-1D7E-45BE-9C4D-076F715AA398", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:98B4E5E0-88EA-406D-8B47-4F416DFAA8DD
,[ThaliCore] Session.session(_:peer:didChange:) peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:56564
[ThaliCore] Session.disconnect() peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B4FF2BEA-7864-4B7F-9E73-4EB43842BCC7
2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:44:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72682503-3E6C-4AF3-B364-3A3C1540F4CE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 06:44:18 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"809FFB37-9982-4C97-A2BF-0029EAC1537F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:44:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 06:44:18 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAd,vertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 06:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 872 passed
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "439F642B-C473-4E6B-8743-D49D9B8F5AA6", generation: 0)
,# teardown
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"439F642B-C473-4E6B-8743-D49D9B8F5AA6","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 06:44:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:439F642B-C473-4E6B-8743-D49D9B8F5AA6:0
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
ok 887 should throw
ok 888 should be equal
ok 889 should be equal
ok 890 should be equal
ok 891 should be equal
ok 892 (unnamed assert)
ok 893 (unnamed assert)
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
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:25 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:26 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 915 verify failed
,ok 916 constructor called once
,ok 917 constructor called with right args
,ok 918 match start arg
,ok 919 start called once
,ok 920 stop called once
,ok 921 stop after start
,# teardown
,# setup
,# One peer with _Local set ahead of current seq (and no this should not happen)
,2017-07-21 06:44:27 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:29 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:29 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:30 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 06:44:31 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 950 verify failed
,ok 951 constructor called once
,ok 952 constructor called with right args
,ok 953 start before stop
,ok 954 We got at least 3 calls to start
,ok 955 at least 3
,ok 956 default 1
,ok 957 1 run
,ok 958 default 2
,ok 959 2 run
,ok 960 default 3
,# teardown
,# setup
,# start and stop and start and stop
,ok 961 start out null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 962 back to null
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 963 still null
,ok 964 verify failed
,ok 965 constructor called once
,ok 966 constructor called with right args
,ok 967 first start before first stop
,ok 968 first stop before second start
,ok 969 second start before second stop
,# teardown
,# setup
,# two identical starts in a row
,2017-07-21 06:44:32 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 970 verify failed
,ok 971 constructor called once
,ok 972 constructor called with right args
,ok 973 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-21 06:44:33 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 974 verify failed
ok 975 constructor called once
,ok 976 constructor called with right args
,ok 977 (unnamed assert)
,ok 978 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-21 06:44:34 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 979 verify failed
,ok 980 constructor called once
,ok 981 constructor called with right args
,ok 982 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-21 06:44:35 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 983 verify failed
,ok 984 constructor called once
,ok 985 constructor called with right args
,ok 986 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 987 should be equal
,ok 988 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 989 Got right error
,# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-21 06:44:36 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,ok 990 Got socket hang up
,# teardown
,2017-07-21 06:44:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 06:44:37 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 991 Got 500 as expected
,# teardown
,2017-07-21 06:44:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-21 06:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 994 should be equal
,ok 995 revs are equal
,# teardown
,2017-07-21 06:44:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,ok 1000 should be equal
,ok 1001 revs are equal
,# teardown
,2017-07-21 06:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/2,8371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/28371400-,394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 06:44:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1002 Our rev is old so we should fail
,# teardown
,2017-07-21 06:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1003 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/2,8371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/28371400-,394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-21 06:44:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-21 06:44:45 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1004 stop caused us to fail
,ok 1005 We specifically failed on a stop before put
,# teardown
,2017-07-21 06:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1006 failed due to stop
,ok 1007 failed due to stop
,# teardown
,2017-07-21 06:44:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1008 should be equal
,# teardown
,2017-07-21 06:44:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-21 06:44:49 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1009 Expected bad seq error
,# teardown
,2017-07-21 06:44:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1010 Different promises
,ok 1011 Timer was cancelled
,ok 1012 should be equal
,# teardown
,2017-07-21 06:44:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1013 One go and one blocked
,ok 1014 All blocked
,ok 1015 Still blocked
,ok 1016 should be equal
,# teardown
,2017-07-21 06:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-07-21 06:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1019 Should have gotten same timer promise
,ok 1020 Still same timer promise
,ok 1021 We waited long enough
,ok 1022 should be equal
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
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:01 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:01 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:01 - DEBUG thaliMobileNativeWrapper: 'listening 56692'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CA9AEF36-0532-413D-8985-EE8AF12BACC6
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "19FD7136-0293-4A62-A234-8569C82F6C79", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:19FD7136-0293-4A62-A234-8569C82F6C79
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 06:45:02 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:19FD7136-0293-4A62-A234-8569C82F6C79
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1063 ThaliMobile.stop was called once
,ok 1064 ThaliMobile.stop was called with 0 arguments
,ok 1065 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1066 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1067 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1068 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:02 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'listening 56694'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2479C34-0D4D-46FE-A3E3-222D2CFBBD16
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:02 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "56F6E2D3-C301-44D6-A170-D7BD608BC7BD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:56F6E2D3-C301-44D6-A170-D7BD608BC7BD
,2017-07-21 06:45:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 06:45:02 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:56F6E2D3-C301-44D6-A170-D7BD608BC7BD
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 06:45:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1109 ThaliMobile.stop was called once
,ok 1110 ThaliMobile.stop was called with 0 arguments
,ok 1111 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1112 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1113 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1114 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 06:45:03 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56696'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A04C8014-6BDF-47CC-BB75-1A73ECEED3CA
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BE39F15B-6B4E-46C7-B44C-BBDE763E07E8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BE39F15B-6B4E-46C7-B44C-BBDE763E07E8
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BE39F15B-6B4E-46C7-B44C-BBDE763E07E8
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
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
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56698'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4534493F-0C5C-47F7-82AC-87C3310720DC
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59A38141-4FFC-4037-B677-122B3B66C585", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:59A38141-4FFC-4037-B677-122B3B66C585
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:59A38141-4FFC-4037-B677-122B3B66C585
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
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'listening 56700'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44050821-4BAF-4B18-8612-2AA6AC9325F3
,[ThaliCore] Browser.startListening
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7A9268B6-F612-4814-8755-96E4D9F9729C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7A9268B6-F612-4814-8755-96E4D9F9729C
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 06:45:03 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 06:45:03 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7A9268B6-F612-4814-8755-96E4D9F9729C
,2017-07-21 06:45:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 06:45:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
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
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
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
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry, is removed and kill is called.'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - ,multiple actions'
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
,2017-07-21 06:45:05 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-,8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,21 06:45:05 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 06:48:05 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-21 06:48:06 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-21 06:48:06 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/c,ontainers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www,/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/28371400-394E-43BA-A787-8197F460381F/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
,2017-07-21 06:48:06 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
