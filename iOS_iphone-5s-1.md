#### Test 113351851520d16b_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/3ECE6958-03B7-4627-BA5E-F8232986730D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3ECE6958-03B7-4627-BA5E-F8232986730D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55185"
,(lldb)     command script import "/tmp/3ECE6958-03B7-4627-BA5E-F8232986730D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:28:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "408E5FBA-5AC7-464B-BAFC-107C9820EA54", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:408E5FBA-5AC7-464B-BAFC-107C9820EA54
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:55C4ECA3-73A5-4E23-991A-34306F5B3FF6
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD4729B5-,3A71-4410-8B80-C81DDA871F3C
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8EBC6E27-DFED-4C9C-85B8-E93827B35001", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:8EBC6E27-DFED-4C9C-85B8-E93827B35001
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EBC6E27-DFED-4C9C-85B8-E93827B35001:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8EBC6E27-DFED-4C9C-85B8-E93827B35001", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-08-01 11:28:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.636166989803314
,2017-08-01 11:28:03 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-08-01 11:28:03 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8EBC6E27-DFED-4C9C-85B8-E93827B35001:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8EBC6E27-DFED-4C9C-85B8-E93827B35001", generation: 0)
,2017-08-01 11:28:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-01 11:28:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-01 11:28:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-01 11:28:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-01 11:28:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-01 11:28:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D8E6D38-EFFA-4630-A9DC-7271888E0D43/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-01 11:28:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-01 11:28:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-01 11:28:11 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-01 11:28:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-08-01 11:28:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-01 11:28:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-08-01 11:28:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-08-01 11:28:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 29 firstPromise - in then
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
,# teardown
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
,2017-08-01 11:29:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9245061B-B5E1-45CC-A59D-4B24FFE99197
[ThaliCore] Browser.startListening
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:29:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01, 11:29:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5916A331-E112-46E6-A5AA-F7FE63D1E456
,[ThaliCore] Browser.startListening
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:29:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3E71C443-A1B0-4961-B081-BD5EE1E704FA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3E71C443-A1B0-4961-B081-BD5EE1E704FA
2017-08-01 1,1:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3E71C443-A1B0-4961-B081-BD5EE1E704FA
2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63
,2017-08-01 11:29:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:29:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63
[ThaliCore] Advertiser.stopAdvertising() peerID:EC51C973-6E9D-4EB2-B33A-3A74CF0B1A63,
2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E55A7F93-0665-4D1F-868C-2BDF896AC995", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E55A7F93-0665-4D1F-868C-2BDF896AC995
,2017-08-01 11:29:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2C205A9F-4329-4E28-852D-F30D5384FF67
,[ThaliCore] Browser.startListening
,2017-08-01 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E55A7F93-0665-4D1F-868C-2BDF896AC995:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E55A7F93-0665-4D1F-868C-2BDF896AC995", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1E2FC6-7693-41FB-8636-0E28C8C7D8EE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E55A7F93-0665-4D1F-868C-2BDF896AC995
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9
2017-08-01 1,1:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8EB29A2A-35C5-4297-B889-08D3D8393171
,[ThaliCore] Browser.startListening
,2017-08-01 11:29:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:29:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FF7A990-8C39-4FBC-B905-C091543C0B8F","generation":0}'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FF7A990-8C39-4FBC-B905-C091543C0B8F (syncValue: U4P3y9cgTo5kYpPMknH36LYpdyLSLLj7)'
,2017-08-01 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
2017-08-01 11:29:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"607A023F-B618-46EF-94E2-E6C7B7C6028C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[T,haliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68DB7C9D-F2A9-4988-BF01-ABC00BA349A9:0
2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68DB7,C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
,2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"172A0C6B-D9CC-4AAC-89D1-604BB3D215A2","generation":0}'
,2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,F7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FF7A990-8C39-4FBC-B905-C091543C0B8F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:29:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U4P3y9cgTo5kYpPMknH36LYpdyLSLLj7","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U4P3y9cgTo5kYpPMknH36LYpdyLSLLj7', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:29:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 607A023F-B618-46EF-94E2-E6C7B7C6028C (syncValue: Dsh010tO9OmOQ2Ou4laYFYvXZax9zUjb)'
,2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-08-01 11:29:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3FF7A990-8C39-4FBC-B905-C091543C0B8F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9
[ThaliCore] Advertiser: session connected Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "607A023F-B618-46EF-94E2-E6C7B7C6028C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65095
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Dsh010tO9OmOQ2Ou4laYFYvXZax9zUjb","error":null,"portNumber":65095}'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Dsh010tO9OmOQ2Ou4laYFYvXZax9zUjb', error: 'null', listeningPort: '65095''
,2017-08-01 11:29:20 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-08-01 11:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:29:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:68DB7C9D-F2A9-4988-BF01-A,BC00BA349A9
2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:607A023F-B618-46EF-94E2-E6C7B7C6028C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65095
[ThaliCore] Session.disconnect() p,eer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:607A023F-B618-46EF-94E2-E6C7B7C6028C:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DB57BA1F-0D18-4357-B930-5C8445B48464
2017-08-01 1,1:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A7E17CC-1455-462D-AE05-2DCCBDD10F55
[ThaliCore] Browser.startListe,ning
2017-08-01 11:29:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:29:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
2017-08-01 11:29:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"172A0C6B-D9CC-4AAC-89D1-604BB3D215A2","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 172A0C6B-D9CC-4AAC-89D1-604BB3D215A2 (syncValue: ZUVYVNTTPl8XP4NqMcFAWcJ8NLzsVEfA)'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB57BA1F-0D18-4357-B930-5C8445B48464:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6D469B9-3E3F-424D-B89E-3EF03B482B87","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F49BF619-EFCE-49AD-936B-BA7E264E926C","generation":0}'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,2A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,72A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,2A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,72A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,2A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,72A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "68DB7C9D-F2A9-4988-BF01-ABC00BA349A9", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:6D4C0CD8-C90F-48F6-A2EF-5523DDCD77D9
,[ThaliCore] Session.session(_:peer:didChange:) peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:17,2A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "172A0C6B-D9CC-4AAC-89D1-604BB3D215A2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:172A0C6B,-D9CC-4AAC-89D1-604BB3D215A2 error: max retries exceeded
2017-08-01 11:29:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZUVYVNTTPl8XP4NqMcFAWcJ8NLzsVEfA","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZUVYVNTTPl8XP4NqMcFAWcJ8NLzsVEfA', error: 'Connection could not be established', listeningPort: '%s''
2017-08-01 11:29:33 - ERROR thaliMobileNativeTestUtils: 'Fatal ,connect error: 'Connection could not be established''
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A6D469B9-3E3F-424D-B89E-3EF03B482B87 (syncValue: yYzp3k5VmMgpnXIvdpfx0TupOtIdP6fm)'
2017-08-01 11:29:33 - DEBUG thaliM,obileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:,sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.init(sessio,n:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:33 - DEBUG thaliMobileNativeTestUtils: 'A,lready running test!'
,[ThaliCore] Session.deinit peer:172A0C6B-D9CC-4AAC-89D1-604BB3D215A2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9
[ThaliCore] Advertiser: session connected Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Advertiser: session connected Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3635C084-2F2B-4106-82CF-D557958DAF39 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9
[ThaliCore] Session.startOutputStream(with:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3635C084-2F2B-4106-82CF-D557958DAF39 state: connecting -> connected
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65103
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yYzp3k5VmMgpnXIvdpfx0TupOtIdP6fm","error":null,"portNumber":65103}'
2017-08-01 11:29:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y,Yzp3k5VmMgpnXIvdpfx0TupOtIdP6fm', error: 'null', listeningPort: '65103''
,Connecting to the localhost:65103
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,Connected to the localhost:65103
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Session.startOutputStream(with:) peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-01 11:29:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,ok 88 got the same data back
,# teardown
,2017-08-01 11:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DB57BA1F-0D18-4357-B930-5C8445B48464
,[ThaliCore] Session.session(_:peer:didChange:) peer:3635C084-2F2B-4106-82CF-D557958DAF39 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DB0C6B8-F703-4591-92A8-677D8F65ADE9 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "DB57BA1F-0D18-4357-B930-5C8445B48464", generation: 0)
2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false,}'
2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65103
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:29:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:29:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yYzp3k5VmMgpnXIvdpfx0TupOtIdP6fm","error":"Session disconnected","portNumber":null}'
,# Can shift data via parallel connections
,[ThaliCore] Session.deinit peer:3635C084-2F2B-4106-82CF-D557958DAF39
[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:14E53D3B-100D-4C85-8359-22BD24E7A4CC
2017-08-01 1,1:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9A06BFE8-2E06-4513-8402-DF87BDDAF892
[ThaliCore] Browser.startListening
,2017-08-01 11:29:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:29:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
2017-08-01 11:29:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6D469B9-3E3F-424D-B89E-3EF03B482B87","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A6D469B9-3E3F-424D-B89E-3EF03B482B87, (syncValue: ytZlE66KThoE6u5JwQmW19EZaqdMj0qI)'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B4,82B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
2017-08-01 11:29:38, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F49BF619-EFCE-49AD-936B-BA7E264E926C","generation":0}'
,2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
2017-08-01 11:29:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13783D87-45FF-4D17-B42B-A653E8B09DCB","generation":0}'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14E53D3B-100D-4C85-8359-22BD24E7A4CC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B83500FD-F735-4993-8A84-3B0EABFD7568:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B83500FD-F735-4993-8A84-3B0EABFD7568", generation: 0)
2017-08-01 11:29:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B83500FD-F735-4993-8A84-3B0EABFD7568","generation":0}'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F49BF619-EFCE-49AD-936B-BA7E264E926C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F49BF619-EFCE-49AD-936B-BA7E264E926C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A6,D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A6,D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
[ThaliCore] Advertiser: session connected Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A6,D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A6,D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
[ThaliCore] Session.startOutputStream(with:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] Session.startOutputStream(with:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
[ThaliCore] Session.startOutputStream(with:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-01 11:29:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1308 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received all data: CtB3Do7fSrsbbNPXw3U6QC9Yd83kZyI8nEI5MpalHIgdQdfxwdP6XlLCqPYhH0ANYG5UYikcvpGQvo3NMqXAek4NBEKy5U7bZAxSEIRdwBn2sPLdlWanuxvCcfZdVK0fErlUO1StcZTP4fN6fSwQLFtFix4g6S4M4U87I1i05oMNKrcHHW,UuBY9RqqfQlbzpDdDbC7loucPYPclsT4jiFkn25rX2euYIPwQHsdQDKbLaxTAhBjhDqzyax5qGHdwPbyVi6u3xxRDENsiH4PPlXFSW0qZoeNm4PHbowY76jmlstyaeZgrD8e4gs9x6SkfCOEAPKayDVxWQWhciP9ac7DTNbZnNjdZByw7rJT3mKE7uimwTx3FVn0EisPDG5bIRATNj7XIrQQahTgKSurtuS9Ode49o7RRPqM9wAGsDC6NNsPvDrK,Fj4OtwztKLi43rKt8zLkEwSwW6IdJzaosyrgcVkNDKT00F9eLHKXCioXNmBoG5Od5JAzIhhFacjCFtXb59kquOzlFXKbCC0bzq8me2kQGtboU1mntINoC5u8mxmXpViQLZBGcYnO9jxaz4MYTZ1ecewrpnZIlhuF9iF95qvDiy9y9p8kHp23z9Xj81JweLd2K2h7siOF4CQfCtlEZBkj30wPqrNsAIIsLHFhryeaMB9A1wEU4JlG6cOF3ZEJnwxW,DDuU5a9PmYBE8Ypz60Hyg0qIdbtDGXSBbmOpBljePiV8vpr6ttNUYkTgN0OznWhyG4egQEKKr7izIHtKXQQJ7zJGPHZmQs9VRrYlTjFLwiENXklEReCtQFgIDlWNnsies8P5sTKr3OQ9lNgQjNkS8SuRYmfh3uoHLtmbFBFkLgG2zYGVZOTc7xbA1o29nV6NvnTL88oaZysWfXZhgz4k3ZuhQDYG12VGhF2Q0iLCgOjh2gr6Sv09QaZ2M2wwHjWM,P6TxZvZA2XhlMcTkhCnOYay4QTTwy2qWW5xqmwCw3C5vPfq5DH6ufIB90g96J4QxRhXNcR6f9lQXl2oWlc2tl4Y6FtIFrD1sePPnjgzQcs0MA0UtmfMRBCABNLJIKKonYnO0rctr5i2v3tnbGy3behiWr7MqM6zecmGEgQQsFavhdSFzJswkVYGrhvG7YSpsxjFrUjndDQHlNxrYVItnQ4QlmwMU64DcGTwZgi6bk7RgLuQusVD7eSdI49JMSM4c,F6Fb4cP3j9uUsR4QAZKyiJzkd2ijliW5v8EaFYj3zygQeAmE0xQ9rVgWzq8hXf6HeW6Qpd0SMY9G4CdV802EfIIqijAyMkqjuSNifIBx9F09M8o0tjl6175cZw7TwyE0dymrFbdC77S56kPOSKlyBuMnjXmOITvet0WLA166edoQt0y1Z9BuW28O1XKrX3HkeR0ucLC0F48Fzd9sRHrWTHJxZPuTsjPmEF7dneKqjGO4mdl2SyxxkM9TohmtiEZN,xMYx8rYchjHb6AMCaMLTzCQfSdWgPVltz9PLmDkW7ZQkIuoNRgN8DT2QyQyLnhGcJbucADiRfAGlucvS8DUaNtfCu2qubR1NQR2R6bpUi1M7nwAqzbYwmpc1b3cnSTd8eeLMJqaaCr7MFhWnHVB7nqbFQLNlV7tzXDb3rm8oGkxYyn8pFvun1demsJWYhdYbyCAesEs1xImoY0KsesFhAv1HHfbp9FQsMupUV0jWiNqJCvk0II11TInrXJCnlsGa,Dic9fjmA0DJV2UjFxu0QbGAB11X3768CjA1qLypoAGSAtalnvG8443YKl7RaUrHfoU6dWdTUTbMyF7pQ45aVKmi7nthIJIyVVGSaPqSRLwVdqqfK85Zbyz9wxsFAvh3WJbm5DEN9EKTpttBnqGhJEW6YE4B8OA0zAJVhyZUqRVFfjLESaux0B4NQ4PzjLS7vVxrOKXEeMOjkjRJrpTZSSWyrvM2MMS95QjODwlYrXOKW4U0V7FwJyAl7ub6Y3Y0B,PkQqZadkhtueXWSYxEvKUzDzE4sUweuBUNskVH4RcvFpQlrkwCN8BHW0mNgBYkbE4qH9Gtgl9W8zCrvtXKi0cQQPKpu3q08VvUirD9EVJ97zJkIgK13cHI6SbeMeO7aBogCFJeLjOfg3isd25kDOnnCgYsvVvhJztz0M82uGQt6YXYkKl1acYp3XdWxnj6jMXXWn1zOOY5HCcmVS1Y6ZrIf0apzVqcbsyTPOpVUS41vucePn8JyccOJ5biNx2t1J,lKEd697ZjUjbskIzXZ8ksQOE3FdrEls6tuXtnR5rsfl8gq3OEdmjmgM5ER0Rap2GVrwLsRnSqTaRlHKdMXKR8rQJ6zZ4OXeLFZZbJ7OYxyeUUGRh4mW5ZwOOs9CCUEYMqvEJ8uyEUy3UHLfgnplpr9bDgHCEmRKXScFoHMEFhZY983GGQZgVuuNfrgjL5jTqexTvMrhJn9y0Vdd5LIhtqnEwUTSQS5iz2UPvMkTZuiOGnsjCiCV9bLODtgARg1y1,zdLEzhsBolmAaLZoiRbbcWpbfPBvqlyQUqCSaO5C3FUOe8eD3EtnspuAx3dxKfCGBXZmrD3Gd8RcyG0lOZeJk7ViSttGcfFol81G1R2Zd0EReHIIG0IVCpJWpgWWggc5EHOJMsqC2xnYYVylCsd4jfU3yTbiIS2J2CwH0f0cSvm2Xm9pKNdDqmbiq06wjaFiHBwNyrjjT2i1Gxjmj7jaRpDB0sXvFmQk6v8un67wdS95JPPuFFopUl7voLHGTBNg,UUjydbOe7ODxU09vtkuCXSYKOLipnV554G3VCJC8IQuzsrMiIPhpCghcpsK1BYWhCd4C6wAU7myJbHLccDxTWqMPRonkGWJw3xYQvrAbaFpTuvAVnIjzWTm3RXRshZlvBBwGJlcCKjBUlpEPFsjq5Q9Ywwm9gjfjq88TzBPSTjG6shJTJ5dgYBjTVeWABrxrQ2leBlBbVNZr43lDHig73QWkYsVGKdyz9UDVgtHWmz2iLaaRuvIlhIgU9V8RMsJL,9YKI9qkLnReLkf0kVvM57tCD8bZyOHLIFkBvyuHzHNW30DQHGcu9uAwkPPMy1rQ23jmitzH9S5dC3wJWVWspkSep7xpvSZW81k03BxbMXJAYLIsYBEdhm8sQkRaYj5QgjxCVDnqudqwCe31oUymuxjL4jC808GWaiYOOGPCIuSZ34KjvMW5MSDflJajfpaCMRu8rJkOQbqR6x3ZWBQkoeWILZqjRJvT74HShuO2yw8q17bCYy7kPmu5UNxPEn3Xg,GXjd27k1bw1mJh6v2qcZ7rXk871Tt27OE1vdqUyOB02zlRSL57ZqSqNVROw7rw0Qnd7b9vq0gywIu0mdrH7GEIvM2rMOp8HrbTBLGavkWlDN1ZEv4svdDsg4ZXkOMSV9e1DtOLmVVcJmE3GMiiXX5nIMdt4MI5M7Nw7viqp47I03sYEKNulWE3nwcH364r7obwlQBVqKkRUyhpAxsPXBgQdV50Xgvy3wRvj6taMD4un67IMDmpE1LIBqVzVg7EnW,Iih24tP3cXXNsFvBIuqX0FQnJWY8QiaiVxvOJWCkV3qRsj2SN7CnOYBf2Vj7v2FzY4vHdaNJPIV0JZKBs6dyirXI1gUJsbtKauY363Vm15jw5lBhjcxGcHnL6RnxhoQWC5bjVFEJH5mnKNzqetqwGhIMwkxkJAqCyAIL5hr4H0XRhkDurv7Jx0RnQZZSNVBMqgEEgl6IqVJkw4k6i2sVLK9uuNnk64P9uTo5RwAQHJbQ4sOAcsaxvOrHjIMyL4LK,EdzJjTgipJVtpgjc7jcrQZeYKMWqU02o7ETr2sYqDz4J8xnsUcyt78pCza981XdBvUnFMo4AOcCjUwLBN6wfrPxS3NtCCgZbO6MiUjcjY75lq8xFItflljF5OFaALcQe4jaUqSUwptLEsiXDeZ7YqqRVgi7yqdZakA9pSDTUSb72F89asq1a8NNHKMJ9m1ud4TlVMd4vr88stA34T5bP3AoqSVv1R5XfdYGO4DvEgSPMA83991CVvqedkXDm2zCB,uwuJOKxC3H4Cyo8ytuF7YpMDwcB8dvbMJHniJAvWJFJA8nNXmBguIV55nyv42vOHTUIsAMkWeDVAM8QQx3qQyay8qkKkRU2GasXoMpKqRKjTtXIuVjRhLO6StCgw8rjTiuN8vyzcvDEHitHCL8wyvbixJnXOo9OW4i3I2XH3NExmbUyMBpCVhe7fsPQN1GirCNEROmVhHfTW3bPcHZ2HDvqLLeB7yZNRumhJpOmsQWhz5lclpINLcEi1RrORdZc0,jkwvfoQt8KrDtCWlzrXh9TmstW8dmRmH2yqLhyplUkCW3YV4Ff96tIQU3aDCsKVOY6dZU57wyYJU3lqK19sDtFXFYsXsIhDDnwWp1ExnPdBCwEsIftsstr9T5Oq3MMHHhjAwBHHg8yZcOJWMwMvJI1qwIK6CsQtHSB4tABCbNqU9ATBsmKKF9cceOeRmVlvGN9Xwdcmzk4yttjDM0zcGqervXQ5eegeL9JMyvNLsw4E9STzWsz92Tqrj5lhe7JiO,A055OuHQawoonDJjzAqnQrfMGNR8U3DIcyI24aI7RPJu3R9XMhffeNOKBIcUCGs9mfDeHEdk4OpswM4Qbs615Iyny09BIuboXDiyz93knpH8dSQ7gWy0kb1Tff2ZemvIoYL9UH95z1eAJB9XLLx9Vu0xJvkmiNay3GAVxrjbDaBMXvlpVQfg9YsSEO9ilayprCQXDNmFU4QcyJqpMEvnza7rmmxCZ6aDlM5ERwbMxn3l98mEAHShV0PnwRjnaX7y,MTBF1ECQXYl1fwLwQHXVevzxZ2aPOAnNwvSW8a0EPpFuNbs6V5PV30ZspSXMBb0BrJwzEAcnMhzO847Oj4wcCmK4v38zGgTQHeN5oz4eP4Im2sP6rRbv5Z16chAC7I383FRAAZHlAAWoo8IacHUbcAZMd1u0sjHE45ujRA3g6xfxVewkWJ9dwl6dRqyimNhpaLb4hI6LZgLIE1onPBk6S0CmNFJLjfPTg3cTDpvXOPgj8U0VXE2CerAImkOnBore,KruQVB48ow5w19GaLIVX1cJyCooK7Ob6vaxrkemxUHbZX6S0jv0O3EZTVVHw6P8yDi0FjMa8jiPzMzj4uiG8OyMc4coKA3gnlNrYKvlZPOLI0pLhbYowSENlLJ4HO3UttwjbvxDrc6cMKE9zrh7mqiOzgsvpAuc2cR7Hi1JULcfmzNQPByDm2o6bCaCNau2oGet5gDKIiRWy1Yuud9v8k7V1ICCVTpaCSSHqcJJzXkKlH2Tmw2e5qvJWA6TUvhkT,bA5U5M8oORbP3AEYVXHrvSqZZHLO6ODgv774smxdpWHtPnRoSuwAj7x8tvjOKgUradKAlhzb2AipMSdyFdT1LBXKIqh2ebhB1BgsgON7BUgqmXnnprJrBpCBeBdnhdY8k7ioT6EojoW2MBoyaQdCza1QDTx75ZCxx2cLmAUJPsb0WhpoMm9p04vM0MyzunzeLE6ix0nh5KJTkXiwcKA4W16c3BprQjKWnF9YbVq95MIjybe967jFi5z8mCrEWtOr,okjwSBuYdeMiexJkZaF5pO8d6LDcR3I2f73iaPsq2ohwVmVvH47MhsdRwYv9OIAex0u7tW3P4c9ja3CM8zq0wBrza4N9rNQDwBZnxGDkMUBribmvNUa8cEdIZ7CrxvqiGy7R3uAPpzuhRr52OQewNrZYERq7CXLqnQOtKVKPEAUNjtynqoN6a90iflAqj1n3vx6DXNmlmKTyXWrO7Fg7RX8cLlGo5YDEhFuRnj3uTqNMV7ChDqa0JCTZQwjqpAju,CWUbN3m8Jmqd4UB8xSculkOwDVJaqTp5ynRXoMqoyj0UqTfdmlJh3jL4yv039ekltiO41up05u12sxshao3sA7oWljVtf4UXmQfwRNqM59ggikPJrhl2jQWJ4EwE5Yk0be0Dat7kGMQbqG5mnjYOpB05dfZu8ONLeJ9LdO8eXjNFoT79CbJew5UeTUdLiJXuaOIgvk5TcqrRznormExKNhqYniuFSS3lezhIYgA4WsNsgrN5dSUISNtozNgaPQMN,OqBMhp58qRnFrsS2ZJskdMHgjtO4jcLFbEn3WLLu1Icm7UYrq4EyHbthWugkfW0COeYa442LnYwcGRuLCLH3nBynwVb7ZLr2SbBwg0IZ0PPqCPOKWgCpu3x627Yu1KiTA1H1d3Nouwjt8xj4yRzSK1BLWYo3LUKXBY6SOt8vHce5hI1uDBFqdbMsCOhQPsYKzoSn56OgdPe7vFVW8f7LK02JVU1lXh55wAd0xFi6YHVvYqzjkkSGF5monTqENARo,by8IO0X17Tq9WOdLXRLC1G0uEF3LZqloFEFv5aoMD0bAabqLPiDqjLzGdxTlH2QkBNrRyOZ93H6c3MWnsuqvJLdKlIsyDsgNY9GsSkuofdoY73CvKmwIfcpjb10tfzMf826pf6bu87PcstoCgnlouqBEeN2XwkUxw1CD5NbjaL7DOkIOjkTJSsPoulQhjcY3jVEl5iOW7IWYFDrZLomblUIQuVGPVDJalzlokPWqt3pYP9iMvKdyjZRpIhn87V9L,rg7lkYZm7iZcsIwfp3c3WfooL9vjBEPYsCEVaiNUgZB1krh4lkFwVVZfMmMsNPcHxu4t2EqbN3cBW9MFAkuDXF9ZAxxcCWdf2VvQgzzRyC6JlUZ3CmihW14zbJrQpJUpY746HGMG5EPGqyX3vDwbWx8iRqtKlReFwJa66HGeQRtyQeA2NQHbJvdRgvAniw7rdLyCcShjmimdcyjrml70CJdkWukZ0htBPfMPT7tmn8ctXe3BYPftP4EJTvXP1hT4,pkImnl86paDMhVZbyriqt74SydRGEf6NufNlsva5E4wjcboSBJmzSmI5pxiAHhj3bCC3ZMyFPcQRTlDyp7dgMBO85JUi7J0S6lqM0ltv78g7IP3xClPlMSnMRhEVsqGof8iETUOdkiPaalvgOKDSbIhTAVgi5i8sjws2FYIQoueI3VsmPt7Ue36QAFpFx5w6CWLfHXQ5gyoV7tYzORnfJEjYxcBdSXqsZNoNCZ03tGu6L02sHWpcrc4Rwxei3XJ8,O396s4FE6m94dTXh3c2VI4PgJuDlW3IVIU4qb1Rpm6ZtKn3nLhUxAWdjnuGMPlwMnTHH6qHyj3SNcHZCEDwBEpSVCZQ6QBd3q8H4VE4QJwqkPZ6hO7nBJW96npuySyHoTiInNM9SDRLcMgBHKh5kvt1l0bBNLkA5zqZaxepP2Zee5A9vRYWKEBZHZnxG1zwPTYmtvm2GEFoK8R8tMKnUERWA9Xk6N1c9vDFJZrPNa52r2Avx1gD8WZwWKXhvzt0A,DSDM11OAEAE76MZ6kTbWb18k8SJCqBql4if4QWobybqL4QbVl8iHZMbTNnCXQKrSnxUYrYKidwPkG7jdUmteaJ8sO4JtwWzIZwDFea9wD0oGJ3EVotUwmRnFj8VIEreoRFF5m5dX1qcgBLweCtCZRap5UD9eNw8HfwEsY52NkAGIMH61RFpNpCwRUIihKbSoNuUlCIIj9t6hWt0p9ptNns5jredvHeXxwscvoTuVRsmJBx9fvfMQnvzNFJj41EuS,P5Lt1JML4tVZyVaPz7EZVuyGL6XM5a5s8Qn8h6EiAP4XFLeB2LRyjxVKhr0PPjsjKtx6i1uYZbCdxGBgfc2KMzQWrsbEIeKUvoOXovqkqRnSjusG05nxfx96DGfk3sBpUr2FFjxywvn9hp1ZYB06UWhmhzHQe4GgQp3MXEIybQ8Iboge46YGqTNW8x4eE98ph6f6qPMOAcFQuzwjaso4GFoT0IydfaqerIliSrxZvsMqX7c2yX4Jc0hMRuSCqQHV,aHmDeAfLMqe7RDksNHCTXo8rAyM5bsLTUhK7Xs2MWByUmkrza18sYgib4lDbz0HVfVMaWYi0ZcoLVVksG78m4XQDo1wwo00Ki8O1hHGZrTsqCFgwNw6uIKlnYzz5tCZc4Zo38oyM3a46x32Am6PHmXfplqCyzP9kkBNCEJdR6ZWA7TUi7yoKr6QQ0RaQ6Iftx9ZY4bWbtKVzVGpFO3dyJg0HAHUG8GFX5fs0lfcelaFxMBMYlgreCn06dNKp0Fxp,q5SLQ4dl4Jy4QlkxR99WBepAVGtkYsdi6IPzqTwjZGIkwizSC5jtde25mdy6VcQdEGr4lHL77qiYh8A04z0yaFDjNfCMqBCBcnPiRffc2788RYvMAJNjRaQGMbB0Pu0QI3WSe8k6tuo3nSBBLgd1zKsU4mFA1TdgTeYnOnlQ2FbAS3zWaFB4AqpCpMQwF8OUVA0sD2SkbGKT1eB7snt9PLk5pyAmwSonzcLkizDbYoxVuvAcsE4FORQmntGfDQNK,Bk02p4x9L8lUarD22GFckVo3jaVTl0WRT7HuNpWOvxxfnbB6RfDv20brAub9AtPFkRtFYZ4zlk3Gw74MND9kYF0Pllmhv0pj48gGnQ9noRMR9uIzzdoM4FWCvmzOZCJEwLsQ7ULbOsWUpCjEsP5RTGOh91Q8X3R4EO52f3PUEUwJv0wSj4vz2LmcXMHZAOeT8BvrxSgxgMKQN9qT5ZVuG6ZYoYMuG4ttjxhMGvTSn5n3T02SIoAQnh20W60o9Y3f,HikzqNb8JyvDXMqmFDDaYcul6VilMVdTwHyyUK0bGJtg2PpzdFKvLbwPUCHyuNxAz4uN7XMh9JpFN2WF58NIibXEUwjgTmBw2vCVy6t3K5U9c1JZcDXDNxrVL3R3OtHbBAiBKrBg43o7k4ntLjNw6263LfmJo4mtihEOr3Ox1hnV5JiA7aY8lXdlLyB35RrMon7pTQnsWNgrIcBFBNE36E5RTzAWPeeLyuuaUvmLIbmrTjsIAIwxVY1tA7qwFLMs,PneZAjMwCEiaoWYWpfqZTNR6BXhSDi9bNlmdK1j3suTY4czlJyW8DKlXojLeGjV35mENLaey4sYXgN2qmNhJidAEre39AwSnh1vNmBaDcOYBqfmmQB61rRSlqAGmI9PMu3tmcACijpetqsO9BOQSTpUPDE1F6vPCb9MOmlyoB10KcAf2k2M2nQwpGhqkLFDlWiEmaV1BWNr1i4hPGNcDDQXz3EeTsXJqtzC3jpSopUB53cwUUJiLc5SEVPHqezjA,km810WNvmweMsa2AVxLOd7BG21WYIcfAkA25cZTeUTFzSdGpTu0EFGd7AYNvnYXV2J7DuT4yU0VPzk3veIb4N3GEvtH4h273cLN1hBk1BriaQ94l7e3bb8PZodAyhji9FMTUnJ97xkOcPXDB5SDCn7rut7m6TlxCapO8naf4JR8MTy8zxvaDIRdXzr9s95sYGt72hXsHkjwTMbz1Dnfjh3MlX3QG5NbauSr7rDzU9OZvyMVmb11NDme39L3g87IC,tYkxCsdjnwZ7CN0nv1hQOKHKzwHu2T25rqZvLdatG6qNZUanrnuE6X6ghsEip5DWVC4wltoPdlOQiOW6RJXJP75bV8HjllMapi4Sh2RBUPt1CN8AyrEBoO9I6NwNh3LM27qIHNw90dTkJlBJNxY0lfNiwJo2XE3OdcNsMQqbOYnsKs6vt2781CsjSGdZ1yL2KzWgE22IZN1c0jlnXK3R4Ep0WppQy4SBZNOznffKjCfTdO7AgCh4fIYlMZNwWjmo,dLhwjO62nckeEwFNLiUqNLVZ0eO4A2ob8GthMLG5GOrihZgX3VmNeYVCR4sVfOmC02ILdsl6QeedqZ42AZIvo03NmpnuWiuRJs24MXOrxtCNKvmZZ2Hfsy8HRHXCm2WJEhUYzj3e0aw2yo1DpjETElhfX1EJV782uShm8xKQqaDYJ6anxVZfJJ7n7WyccCGkOhYt7KRiuKZZplrET0sf0kIJD5uqwGMvr1bBJgnDcRvVArScn4ytlL0BDHQ6DVcv,pdZ7gBfwuVKhnqo459E4jPCd74buwdFob10Bb6pHaTbQyn20pulPYLdZ69sY0EKybwX88TCZMNjpKmdWwN5em27phi0CE2vbZG1aO6eB66WeoVIMyggI5HAUZm1Psk5Z0R98pYTeODHYdtbVRs9yEXy6WnXJNHWu7TCoZZeSKxPIsn7zfgtn0EKYFWKO0GI6J1VPabJHsQf05X4OzzzrxJeNo5P0K1dNefYa3onUbjY7J1u4KjpDk6nGwJUxjM8L,EHQOt0GwYlphDeh4kllu8nUJxI0l9ymr6BJv1Lsana1i3lDGIOb22A3ssUAeHNXr9P0PZ7i7RVXxgGBO3sayJm89CAOrluQTjsNSFLf2nm0OA8c18C8D9pY3qLOkoczaSNmScy6DtVdBqGPaeKV61iLiywBPG6GqrFCxJ3Mm01SQyGBYOOVsoXujpqvfYE1U5mOA2fCPEt5iolojdbhinf3tZ1gnMze1flJ4voU22FU6GlV6llsstaKGzBCjEq67,ukwwU67LnBflT6KFazZrM5DSxc76DZVRPF7pLUJmKMJbNNJYXdr5Wp4agIwdCfQhlJfoOULuqGFDk4C8URarObOoGPLsYyGrKlnUxJY3iaAJ30tSL4USUXCVfoEn8wMVcsDXHTC1EthZBhrFNY9MAoNCWUyaLWZSZJFl1qrIayDnm2xorMFVFjWNnCVc9WrTOaqO6UWCBNamM1hHIuOwxQ3ZFPn5DBZKdgGlNVSLO4DebUEd1x4UsMpdlo0zIEYE,Wqaep5kTGyeIvRMTEBtPLD7EJMcxxOWSDcctnh1IMYDdH9h2OSSGodys0NWQNJq9DsV9kbY4iTHvVw1METnQOkLxiEnEPJ8CCfmZk66LzpHCI4ytx5j78TwZvU2DGdlR1YUGwdZPWNozC6pbLUpXsLHV7egdFpnehNOJD97GrqOz2kAxIwRf89MwKfktJ6qFlyAMhnIl3W5qJjjt5b9GZJvbTfLehzrovoUfKarvJF1WE4gtAeIKr2Kh398J3Ami,Hy3qBWljPv3wKrl1QbtgdpoVu9YS3ctFRvrsVnGE4KUxcxC1zFkTx7sGcqTohvwAJwOry3DAr2rUBkRW2o1hXB5unjY4SkyaAMmKGZ3tFsayTq6mzBrU1uVRivnwnY9HgVlj72sYDt4YTKlqO42zjb7et3dQwjdZL1swCjZQgmw2NRiJt8YQzUQztWHG2OTEi04VF8HZfyFoSlq3UEQsZJ4VPETDieqT1ecAgkjsfBlsZVXuwrkUethm1UVWQ9oB,tF5KodGSfwOSZqs8TyNnkfo4e0mqTlbcux5483dcFRFOfukY2Anx0vf5Ako0X8lilburAQNBgqITDYKLev7HXVwAnou4wkD0pup6v3Tu5RUEKPHBadpze3U7MTKhVULiAccYjQP9s7PNJEZ1x7SN510UjFqGTXI8dbz9E5tNfVxKzBTWoll4nw1tZKWyQWeZ2M7mSkJcEyiGXRx9ABcDD12UjjiGvkzwqa62GCZNnKyu9qjCw9GDobW8VPUQTCKi,zuEnnP763LPAj88wYwpxlTPgTLRiP83m62DOzXCKQsLpnGNQJQANnFYaq4HRPYpFcdwrvnXdGRiQDYcFcVuMjK3agznWVNzTme9NtG7XycjfviOF1frjSESWspTVbf4j5O9bkmnDnlwY8sj2I2Ku4SggcYAnBd5TT6OxF9kyPZTUUAWQRnekmlDxZGvFrLfdNqfZE9Q6uFdnhWlltgK2CpWA29SvbcsXVwERblxRn3ByQu8QZ6yQIEJQHkPACLbT,5lRrOAHk2iDAMgNJ2LKCSTFZwQEYN5zmxi36vdLdmGgcz5a6aWWw4w4r9aVF9doVv3tv36ycGLbbhAZkEsps1fj0MsVxGx59PvPPHfQBqyJZApZQtOvcxbk8WviW7bzqUyt1tKUPfdQgUEWJlqM0K83ExoDj5JTCXwP4pGev226zlMRQLMcQmdNMu7RADt2a027ZROBlHIyGlAolRnHosczUtGXWH6YUQIpG8lkZYbLfEbYJadPKLL1mijcRkBB1,XVXjMjkNbQieMYTxgmECqCXV83X3JB3Jbo8YVa7K4inQYLn0hKzpNEIUryTVczWkgDU3yFum8MkHvC26sfRScFUDBLXCYNAKA4ubkHTv73TXWhpNLAB5nR56oE8txP0lk9WO7nKhS3x3VY8aQwSwZCwrTtVfk1LqBK7QcJ8lnEIiZtI3KlO9Atoaodbr65tHFS85EIBKMGNVudIBDnEGNZAlMlhWLq6z9jvyJ8HkG8KcA8FQqUnjQnQ5bB5tS9c4,omEnEvTDZXL3QTgQ5KsuzkBTZkOqcE6ixHGSFMkAFljh8VjGI3oPg5pi3G6ElxtFVFqhPip3V3upEZQgUqXpul36heHK6ac3DCpUlfiKmw7Y2QFKKSmkw0qYLusTsUU3vtfwpecRmbE67IVR05ljo3Xnn9cG1iPnsAKzIqlPxDRjAaKeVWVoL9Qpw3mZb0SOxEnSeqlO3dkT1ytk2CisSKzCqMiwxocjdgTZOQMCRDuzBVhRfYGKyeLxI4ohKmbw,4PAJQ6XC9FQ1OLpqlSH8aYb5CfTwNldMGYrCalLb2h477U3qPHTFVRIJyT4wdD3vMDy2pc0sD6gkzlXmuu74wZrwgHnzJl8QwdazpVhsU4fZV9YVtsi1pKTOGqCjCLnpe2Ax3Ax2p0UQGUYWQtA6Z0L3B3AScZZ3pFi4Ukzq55SSSP62T9V4cvviVq0RQ8Bc6QANuPZk8bdjJggYCCTZ9irAXv6PTqWxLOe9WQ6LIxUZSjaZI6zZV30IowKMjJbg,zwU5dEPsDxUlXwUETyjhJl0rlNvTx6BwwAJcREG6vNz7rQXFL3a69r79Nz1FXTyLbWIDS6THT4WDHEtWk5N5mH20sayX6dbCshVdJcI2KONIBW040PnIvmp7OF6YQMGDlu7zs9oNV9vLFSvVGNP7tt9uG7B7o0JBJERuVaNXIefWc7ccBpvEKNAUOlLJw9kvl7p547PNIQ9DhM8y48lwuog3FHGlk5bRtNw047wq2khWDJsDc2uph9fj9v1eyJAN,hb00UPVt5uC21xytNg8uTz5wHs6HU1oympVI4RCDVCwhMEazCeC76DQ1dBILqdjMeYoar2oN4GdfywI7UzIhTECw1sA7Bmqma15l3BzNW6DYMv8cLgVI6wM7Vf85GJpl3RV7Gh5jijmTqGSTF6Vjf9j1cOH7UlIiXGwkkalO08jmF4WfRE2Ed1w8TKDnTBJVqVj3QReFhwTaeF58urVQMtYPWRiaedlaLEzuctenZvBYjDgZVGOcAuTbdbyHkAGm,IgysvezXH4RF41p1MDpX82FzNuNxEaFsExRzlaH086lnyZgutJ7PrQf6X34xidlO9sqcvt4C31EnCsHKUqQ3VZt0vrULFDtOJS0ghn6Q3qfNOHfUNANFBGYUgOYkTokRCEfZvvzufTbUqb3i1MKBywXX22sApaFUPEhEICLS3qdm3w8zNjHf8j0cAirKEEP9tgx065pZrOPfvfPYeDbJbozEYbbKyAqKaTSmFK3mwf3FvmGQV3rb5jpVI0e0P490,cUP9XiihpkCnoyKeWpzBATdztEb14AWSc7t6K5yJt9Fs2Wiy1CzkYxffCp4Frnx6lCNvMbfguRsg3OG2KcrtxnrWrIa26DBlpLGx67Sl3Gr7SHBrDyJaITaUwIVQoigj6xJrly2gpJnfGuEVYOjOAscs49z9KBpEDW3Ri0v911oW2Q0qDNO13Dn84slNxz5bKznF6UBNRzJcgWLc8aIRWoM2t2L8fT9juiwBkP3hIA45AEzyGFzI9c7NVcEEhKAt,kdpV8vHbS6bIeFUO5SoKep7OvEx8uMZBpvvHyi6BYAstqTZt5PYWRXiTKxSqd6GKlW4101dD7VUsmtxpicjs79aqlE7cfUuxnenAa0qt9a19VZHvW2bAEI7NZToxoNgLD6PCDSJqckpvEhyFPPWQX5gyMMI2XmIIEQe1HqZGmFuTbmBfVIXPnUpxmU2FCps2re3VFQm7NFCzosRPYIgO3xkw0up2NNALDIsSfvDZyNBFs50vSP4RjesIB5SmKHC8,zp2YSK4aUu64Fy5fyIglTbg8IPuGU54TnvKqiHhoEWr5yUv3P4BhyGuBjpeNxljQyqoe1JzWvEnayb7GEr6VRtPtmDpTXU51eRWvltxWsFzQLHsNMQI4oy5jXQMyTKjuh6ZewzLczDeR03lX0Vnw6EEvMRYf5sMqs6NRcSERVYZpPtMYtXdaPzn7EJxZU10U6r6Pvv7jMSyRPE5hcf7bbGHmJIGRE0jAwBoEkxBCZnz3bSZX1Nleto3iOrQRfoR4,vBTfa2Ix5xJ5tksr389sFpafCdPdW9s3KcowYVP6h636fOPGUdViYdKngwa9c5SFWVHyZuGhnbv2KGLvKWcJuw4sTEtqGgK2rqgyvjVtZsqLRgv4y1TW9QvV0gtg1LVUAOQEWV1ZH1JS1vxINb2BiQEfvWpNOADhE1IhF6MoZYCoaBwoQu9njetqyAbKEhkokAFagF1v1et2aQz7a9Be24mSMh0Hel2e1MIkZZuMBKhCMXOQDXaLHtDuyUpHe3UV,7lSy4vVeHzBbGRGn5TCHN72qVm4wWRbzZeX5Bn5TfAOjAwOZ5YF0QZunQkNLPadpBxsSvMO8bbr74WGz8J03ltyGF6u6r7WSLeQOl1nnOqJBNUsrgpxlGJPzDTDk4jkvzvAGfcmciFIhpzCutkPSTYQhD0lLicXYEhU6UttupBw4kAWZurFz0i2nDFP5ay05gnbLBVNlVpq6KjrX3v80G5JSTkImATNnO5zDy0ckwdxTH7ZEO9nPSd3xoBMkLgFc,VMKl2zsOkfQqpHnPyYgXO7ifRcUDOKmbZN5glHhuUB0uc8G36RpqH8XyfBioLt3MIFwX2EWwsNbOF4gqVw5cuGZovMaClkL21UWIhL4WbvuR3elJr3ETM84mGsi9HquoaihE10L08djgxwjHz2EuMtDQzHvm5tL016OySyKvwgyZxu576owUoZRWr6hFEWQ05CNW3txM5UfhmEpdXWk8SQ30E0SeKkb8fmx4pMzZg4mhx6DlsSxej2y8Zso38t05,ynbFOzS3vdtZ6bzAZFMfOdJT3GXs5rsX4x4TuqIPhfxJabXgCarhTPu5ZG5s3PMQvmfN2n9brmdtxXUtDvz3c5EUsntnVT6Y8NudUMlpW51pI05cPf3zifwk4fuUgG3axbQxfgL60zwaMtApkv4mcKUWm7HpQIZDtomiylh0WXq8axbdlYMJjTF8blO5jloqUdADAKdpCJhSELghM1rOi7cydViMnsJZ83pdVBujuhx7Q9fU6mIk9ndCVnxzLPUf,EsqxwAkWId9Wv3dn1fV51LhLT8eWnGROuTNDgdPzQ3DfySZlPsFCv6k15pdPPSOD0Tr4vD33vcnpFFMaQbzlbccpWXq9I33qBvWSqS8QXVVOMdgVROt4YRwPjP8iQK7lZe4jTpVlQHgxMi8rebGbDqxYUnLD0JHiO6VmN8dsGmrHo54jA801rtjiwCFPRRth4GUCrSKUvfkTCzAA0twcu4y0IX0WxLYFMVX1LitYJ3NInkMdfNboPatuzBq5yKgo,UGXKSw0wDREIxuhoGGHsCb1KQZiAwK8hhRSfIPdubhh22XhK6Cvs4oVsAXVRVzl266oXMIhSJ8xTZt5mSjiQWkvGc6xJboYNRvERB3NMFupRdXluCxsNt9wIWnhDxqp7y8HQ5Og5Pg1Xr8q079sVQjHs6CsDbMdA3ytmFSICGb9oAenZEUUS5FkHjlJo1Zkr9VWmrCfk6W0fnkqHgaxOECvyFobGmBLBSN0llZ9i7gajMWMG2HwxpKZtGqNvSUSt,WWQYkV1n6pir0cJZGLElFBYP6NpkheOusw7Ef0txg2zHWlMwVfS1xL63uTrI4VBiQVvOVsbjgImOeZE3kMV5gbHz4uLib8DrSrhviG90hLqwp4B5rQ59JIOnlgsbvarMwWS359ECYxjNoe22GVFW3tYLBOPtgClGrpj6f0n8dTT58bKdCsb6qta9IOLSGVWEhDe96qGJ1XbppqQiES3Pvlij1fafBSw8flzeHZJcgYwuhUnXEG9K36esVr7hZqQj,ilCil29LUFWlCuLtVXRGuGyXaAP3772F41ezzdxTO8SOyex5SjEQYqGQEEQkWpztM9v5zLKQNQaB93pObmntBUSDrzK3kbA1FgwEyTNHpHd6q1a8ARY1i4Xx4FlYJNqSXStaW67btRzlgqHdd9GLch04yidEykjg9zlgKSgPbTekMY7ME36z7O07Ome9H96FidJParGcD9uRn5mJeW4oiptvts6YzV0Live8fVos31EtFOmgnfCDyRGIb62CBbKE,lDQvJC2zMKtW8cqQDF0x70c8KXNUAJUkhoHTqmvg6lezHzSiuaM00ROH7qhWtNeGdcIUfjBnRJ2eCq'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 4, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconne,cted
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-01 11:29:47 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A6,D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A6D469B9,-3E3F-424D-B89E-3EF03B482B87 error: max retries exceeded
2017-08-01 11:29:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ytZlE66KThoE6u5JwQmW19EZaqdMj0qI","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:29:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ytZlE66KThoE6u5JwQmW19EZaqdMj0qI', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:29:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:29:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13783D87-45FF-4D17-B42B-A653E8B09DCB (syncValue: vDGAgsQ,RbpvyqvOdfppEagRhRU33VpJG)'
2017-08-01 11:29:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13783D87-45FF,-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:29:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A6D469B9-3E3F-424D-B89E-3EF03B482B87:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A6D469B9-3E3F-424D-B89E-3EF03B482B87", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65123
2017-08-01 11:29:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vDGAgsQRbpvyqvOdfppEagRhRU33VpJG",,"error":null,"portNumber":65123}'
2017-08-01 11:29:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vDGAgsQRbpvyqvOdfppEagRhRU33VpJG', error: 'null', listeningPort: '65123''
,Connecting to the localhost:65123
Connecting to the localhost:65123
Connecting to the localhost:65123
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,Connected to the localhost:65123
,Connected to the localhost:65123
,Connected to the localhost:65123
,ok 91 correct string length
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-01 11:29:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 4, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 4, 6, 7, 8]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 4, 6, 7, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 4, 6, 8, 9]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:8
ok 95 got the same ,data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TC,PListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
ok 96 go,t the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 4, 6, 9]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 4, 6]
,# teardown
,2017-08-01 11:29:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:29:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:14E53D3B-100D-4C85-8359-22BD24E7A4CC
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:13783D87-45FF-4D17-B42B-A653E8B09DCB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65123
[ThaliCore] Session.disconnect() p,eer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "14E53D3B-100D-4C85-8359-22BD24E7A4CC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:29:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[ThaliCore] AdvertiserRelay.deinit
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-01 11:29:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:15A58A4F-9263-40A8-BBEA-9BB3A3562A84
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3119235A-AF7A-4ADD-9B55-A83D97083E39
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0674F720-4FB9-4890-AA34-55A602AF,7964
[ThaliCore] Browser.startListening
,2017-08-01 11:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
2017-08-01 11:29:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"13783D87-45FF-4D17-B42B-A653E8B09DCB","generation":0}'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 13783D87-45FF-4D17-B42B-A653E8B09DCB, (syncValue: RQIpk2E5mv6otEqwX8QGAGXyo5rwDLE2)'
2017-08-01 11:29:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B,09DCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
2017-08-01 11:29:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BCACD4FC-6BC5-40D6-9610-1040266CBCE0","generation":0}'
2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:29:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"709BCCF3-BC4B-4608-9082-D26EEC5531F5","generation":0}'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:29:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3119235A-AF7A-4ADD-9B55-A83D97083E39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3119235A-AF7A-4ADD-9B55-A83D97083E39", generation: 0)
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "13783D87-45FF-4D17-B42B-A653E8B09DCB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:13783D87,-45FF-4D17-B42B-A653E8B09DCB error: max retries exceeded
2017-08-01 11:30:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RQIpk2E5mv6otEqwX8QGAGXyo5rwDLE2","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RQIpk2E5mv6otEqwX8QGAGXyo5rwDLE2', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BCACD4FC-6BC5-40D6-9610-1040266CBCE0 (syncValue: u496M9S,6EIJQcCX8QC8cR1qmxHiN3NNj)'
2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BCACD4FC-6BC5,-40D6-9610-1040266CBCE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-01 11:30:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:13783D87-45FF-4D17-B42B-A653E8B09DCB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65141
2017-08-01 11:30:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u496M9S6EIJQcCX8QC8cR1qmxHiN3NNj",,"error":null,"portNumber":65141}'
2017-08-01 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u496M9S6EIJQcCX8QC8cR1qmxHiN3NNj', error: 'null', listeningPort: '65141''
,Connecting to the localhost:65141
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 4, 6, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:65141
2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-01 11:30:08 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:10 [1, 4, 6]
,# teardown
,2017-08-01 11:30:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:30:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3119235A-AF7A-4ADD-9B55-A,83D97083E39
2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65141
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "BCACD4FC-6BC5-40D6-9610-1040266CBCE0", generation: 0)
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:30:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u496M9S6EIJQcCX8QC8cR1qmxHiN3NNj","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:BCACD4FC-6BC5-40D6-9610-1040266CBCE0:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:30:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:844E4EE5-1A48-45AB-86DC-C6E9AF19AB4B
,[ThaliCore] Browser.startListening
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:30:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
2017-08-01 11:30:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"709BCCF3-BC4B-4608-9082-D26EEC5531F5","generation":0}'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 709BCCF3-BC4B-4608-9082-D26EEC5531F5, (syncValue: gQne62vN74kXKpdY1QanV4VG5n4BD9qg)'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5,531F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
2017-08-01 11:30:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}'
2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7D1DD656-98E9-4642-8F1D-2B7D93F24C5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:70,9BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,09BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:70,9BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,09BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:70,9BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,09BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "709BCCF3-BC4B-4608-9082-D26EEC5531F5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gQne62vN74kXKpdY1QanV4VG5n4BD9qg","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:30:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gQne62vN74kXKpdY1QanV4VG5n4BD9qg', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:30:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:30:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8C4149E0-9EF7-47F3-AF61-7B54D5101639 (syncValue: ny4bJq8BLFeDA2wqt4eTvEJ,Tsh9GrCZf)'
2017-08-01 11:30:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8C4149E0-9EF7-47F3-AF61-7B54D,5101639:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:709BCCF3-BC4B-4608-9082-D26EEC5531F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
[ThaliCore] Advertiser: session connected Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65155
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ny4bJq8BLFeDA2wqt4eTvEJTsh9GrCZf","error":null,"portNumber":65155}'
,2017-08-01 11:30:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ny4bJq8BLFeDA2wqt4eTvEJTsh9GrCZf', error: 'null', listeningPort: '65155''
,Connecting to the localhost:65155
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,Connected to the localhost:65155
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 4, 6, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-01 11:30:24 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 4, 6]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
,[ThaliCore] Session.session(_:peer:didChange:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
,[ThaliCore] Session.startOutputStream(with:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 4, 6, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (37230 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received (1540 bytes):'
,2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-01 11:30:26 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[Tha,liCore] VirtualSocket.deinit vsID:12 [1, 4, 6]
,2017-08-01 11:30:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7D1DD656-98E9-4642-8F1D-2,B7D93F24C5C
2017-08-01 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65155
[ThaliCore] Session.disconnect() peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E1987A65-4FE4-45E2-8BDF-0E447463D722 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7D1DD656-98E9-4642-8F1D-2B7D93F24C5C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
,[ThaliCore] Session.deinit peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:E1987A65-4FE4-45E2-8BDF-0E447463D722
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:71AD19AA-2DA0-4B80-B6F2-ED1E84B15A45
,[ThaliCore] Browser.startListening
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C
,2017-08-01 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:8C4149E0-9EF7-47F3-AF61-7B54D5101639:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C4149E0-9EF7-47F3-AF61-7B54D5101639", generation: 0)
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}]'
2017-08-01 11:30:29 - DEBUG thaliMobileNa,tiveWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8C4149E0-9EF7-47F3-AF61-7B54D5101639","generation":0}'
,2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D08031-1F9F-45B6-A50C-99D850E180F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D08031-1F9F-45B6-A50C-99D850E180F5", generation: 0)
2017-08-01 11:30:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B1D08031-1F9F-45B6-A50C-99D850E180F5","generation":0}]'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B1D08031-1F9F-45B6-A50C-99D850E180F5","generation":0}'
2017-08-01 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD3FECF4-CBFE-4AFA-8379-AD80173A0C4C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:30:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AD3FECF4-CBFE-4AFA-8379-A,D80173A0C4C
2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05D63461-4BCC-4063-B0A5-1597954F55CD
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2E91F407-D462-47E2-BD54-CF2F18ADB1CD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2E91F407-D462-47E2-BD54-CF2F,18ADB1CD
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopA,dvertising() peerID:2E91F407-D462-47E2-BD54-CF2F18ADB1CD
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
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
2017-08-01 11:30:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-01 11:30:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
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
,2017-08-01 11:30:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
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
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:db8b4fae-f64b-40e5-af1a-a79a6bdebba8 error: startListeningNotActive
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"edgzbEO8Z283s03dJwb1d2v1B4BDmC4c","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BFAFD178-962B-494C-977D-07DFF67E9550
[ThaliCore] Browser.startListening
2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:30:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:30:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-08-01 11:30:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZQd9bXoLWxymOyx7dP0wm70yeJijDRWw","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
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
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:30:42 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DA49F00-86D8-45D1-9CDC-F4C4F77D05CD
,[ThaliCore] Browser.startListening
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01, 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,[ThaliCore] BrowserManager.disconnect peer:c7dd5a4b-fa85-4159-a3c8-4213e6bf1557
,ok 140 No error
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
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForA,dvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3038AF95-16B9-4402-AECE-A2CC49BB5D40
[ThaliCore] Browser.startListening
,2017-08-01 11:30:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:30:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08A37317-9245-4816-9BBA-BFF468DCB1A3","generation":0}'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 08A37317-9245-4816-9BBA-BFF468DCB1A3 (syncValue: MCni2yV1VAZ3VbXmy3a7Bo2k12PkYL09)'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300","generation":0}'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5DA9D523-DC1D-4083-847D-41E967413C38
[ThaliCore] Advertiser: session connected Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5DA9D523-DC1D-4083-847D-41E967413C38 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
2017-08-01 11:30:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C8FCF81-7CEA-409B-B47C-33B13E726DA2","generation":0}'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:30:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5DA9D523-DC1D-4083-847D-41E967413C38
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DA9D523-DC1D-4083-847D-41E967413C38 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:08,A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,8A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5DA9D523-DC1D-4083-847D-41E967413C38
[ThaliCore] Session.startOutputStream(with:) peer:5DA9D523-DC1D-4083-847D-41E967413C38
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [1, 4, 6, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:08,A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,8A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:08,A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,8A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
,[ThaliCore] Session.deinit peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:08,A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "08A37317-9245-4816-9BBA-BFF468DCB1A3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:08A37317,-9245-4816-9BBA-BFF468DCB1A3 error: max retries exceeded
2017-08-01 11:30:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MCni2yV1VAZ3VbXmy3a7Bo2k12PkYL09","error":"Connection could not be established","portNumber":null}'
2017-0,8-01 11:30:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MCni2yV1VAZ3VbXmy3a7Bo2k12PkYL09', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:30:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-01 11:30:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300 (syncValue: J2Sv2rK,j4CI2QFLJuSvOYkkC95jXMie8)'
2017-08-01 11:30:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A0C3DC3-7791,-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:30:55 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-08-01 11:30:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:08A37317-9245-4816-9BBA-BFF468DCB1A3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65173
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J2Sv2rKj4CI2QFLJuSvOYkkC95jXMie8","error":null,"portNumber":65173}'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'J2Sv2rKj4CI2QFLJuSvOYkkC95jXMie8', error: 'null', listeningPort: '65173''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0) found active relay
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VK4lqM5nysutc8xTYinodk7vjOYuUk7Z","error":null,"portNumber":65173}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 4, 6, 13, 14]
,ok 144 No error
ok 145 Ports equal
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300", generation: 0) found active relay
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iLPyQeNBBj1KyqwoEBmGmA8D7Zth0Gr5","error":null,"portNumber":65173}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-08-01 11:30:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-08-01 11:30:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with ta,rget ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore,2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:30:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 4, 6, 14]
,[ThaliCore] BrowserManager.disconnect peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65173
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] Session.disconnect() peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] Session.session(_:peer:didChange:), peer:5DA9D523-DC1D-4083-847D-41E967413C38 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0C3ABEC2-EDE9-49BF-9CEC-7F09F581009A", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.dis,connectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:5DA9D523-DC1D-4083-847D-41E967413C38
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 4, ,6]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4A0C3DC3-7791-4A79-AC3A-13A5BB3F1300:0
[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5DA9D523-DC1D-4083-847D-41E967413C38
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
,2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-01 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-01 11:31:01 - DEBUG createNativeListener: 'listening 65176'
,ok 149 Should throw
,# teardown
,2017-08-01 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 65178'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-01 11:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 65181'
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
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'listening 65185'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-01 11:31:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
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
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 65190'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-08-01 11:31:03 - DEBUG createNativeListener: 'listening 65194'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 65198'
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
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'listening 65202'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-08-01 11:31:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
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
,2017-08-01 11:31:05 - DEBUG createNativeListener: 'listening 65206'
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
,ok 177 native server should be closed
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
2017-08-01 11:31:06 - DEBUG createNativeListener: 'listening 65258'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-01 11:31:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-08-01 11:31:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:07 - DEBUG createNativeListener: 'listening 65262'
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
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 65265'
ok 196 port must be in range
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 65266'
ok 197 second start should return same port
,# teardown
,2017-08-01 11:31:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-01 11:31:08 - DEBUG createNativeListener: 'listening 65268'
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
,listening on 65270
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DEEE1C2E-DFA1-45B3-997B-1D11C47CA194
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
2017-08-01 11:31:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C8FCF81-7CEA-409B-B47C-33B13E726DA2","generation":0}'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C8FCF81-7CEA-409B-B47C-33B13E726DA2 (syncValue: WzuCvof3ngIASaRRDBkPzdyMARyXKxxk)'
,2017-08-01 11:31:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
2017-08-01 11:31:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
2017-08-01 11:31:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:10 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5AE67C3A-6330-44AA-8E2E-D189F55382F0","generation":0}'
,2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23
[ThaliCore] Advertiser: session connected Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
[ThaliCore] Advertiser: session connected Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C8FCF81-7CEA-409B-B47C-33B13E726DA2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:31:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WzuCvof3ngIASaRRDBkPzdyMARyXKxxk","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:31:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WzuCvof3ngIASaRRDBkPzdyMARyXKxxk', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:31:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:31:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817 (syncValue: BubtCHBCGwRm0UbvWzU2kyi,LFxpulLKi)'
2017-08-01 11:31:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1,F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:31:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4C8FCF81-7CEA-409B-B47C-33B13E726DA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23
,[ThaliCore] Session.session(_:peer:didChange:) peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65280
,2017-08-01 11:31:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BubtCHBCGwRm0UbvWzU2kyiLFxpulLKi","error":null,"portNumber":65280}'
,2017-08-01 11:31:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BubtCHBCGwRm0UbvWzU2kyiLFxpulLKi', error: 'null', listeningPort: '65280''
,ok 210 should be equal
2017-08-01 11:31:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5AE67C3A-6330-44AA-8E2E-D189F55382F0 (syncValue: 8bweSQzaoRQm1OmMVlUOE9KHqVp0QlmX)'
2017-08-01 11:31:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A,E67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65284
,2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8bweSQzaoRQm1OmMVlUOE9KHqVp0QlmX","error":null,"portNumber":65284}'
2017-08-01 11:31:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8,bweSQzaoRQm1OmMVlUOE9KHqVp0QlmX', error: 'null', listeningPort: '65284''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 ,11:31:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BA0DAC81-4292-4CAE-9C1B-4,EA82DA7C4B9
2017-08-01 11:31:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65280
[ThaliCore] Session.disconnect() p,eer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65284
[ThaliCore] Session.disconnect() p,eer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:31:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[ThaliCore] Session.session(_:peer:didChange:) peer:D9C5C18B-152B-4BD5-858E-56BE4F5FEE23 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BA0DAC81-4292-4CAE-9C1B-4EA82DA7C4B9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-01 11:31:22 - DEBUG thaliMobileNa,tiveWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:0516D8BE-20A3-4E3D-AC6A-090E4CDC6FEF
[ThaliCore] AdvertiserRelay.deinit
,# Multiple local http requests
,listening on 65286
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-0,1 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:78615FF3-BB41-476C-AB03-7264399F5297
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:79CCE9F1-59ED-41FF-92B4-823C0E611D3D
[ThaliCore] Browser.startListening
2017-08-01 11:31:23 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5AE67C3A-6330-44AA-8E2E-D189F55382F0","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD00B2C6-79FA-4A27,-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5AE67C3A-6330-44AA-8E2E-D189F55382F0, (syncValue: QEx2bvOtGg2NIQmesad0EpurQX7lEmgw)'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A,E67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817","generation":0}'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
2017-08-01 11:31:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}'
2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-01 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78615FF3-BB41-476C-AB03-7264399F5297:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114
[ThaliCore] Advertiser: session connected Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,E67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5AE67C3A,-6330-44AA-8E2E-D189F55382F0 error: max retries exceeded
2017-08-01 11:31:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QEx2bvOtGg2NIQmesad0EpurQX7lEmgw","error":"Connection could not be established","portNumber":null}'
,2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QEx2bvOtGg2NIQmesad0EpurQX7lEmgw', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-01 11:31:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817 (syncValue: VYfecL32v7rfdM1tHGQGcdudF7pTnybR)'
,2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5AE67C3A-6330-44AA-8E2E-D189F55382F0", generation: 0)
,2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Session.deinit peer:5AE67C3A-6330-44AA-8E2E-D189F55382F0:0
[ThaliCore] BrowserRelay.deinit
2017-08-01 11:31:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114
,[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114 state: connecting -> connected
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
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84056088-3896-48BB-8E52-4509E9BC57C6
[ThaliCore] Advertiser: session connected Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:31:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VYfecL32v7rfdM1tHGQGcdudF7pTnybR","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VYfecL32v7rfdM1tHGQGcdudF7pTnybR', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:31:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-08-01 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2 (syncValue: NZW7NXiFtGUPp1fkI5n90HLBXWVMwama)'
,2017-08-01 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-01 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DD00B2C6-79FA-4A27-BEDA-C0FD1F4C1817:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84056088-3896-48BB-8E52-4509E9BC57C6
,[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65310
,2017-08-01 11:31:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NZW7NXiFtGUPp1fkI5n90HLBXWVMwama","error":null,"portNumber":65310}'
,2017-08-01 11:31:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NZW7NXiFtGUPp1fkI5n90HLBXWVMwama', error: 'null', listeningPort: '65310''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-08-01 11:31:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A (syncValue: 0icFCe1fNb8RbuwRPqtjUE3Ea5skwpNb)'
,2017-08-01 11:31:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65316
2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0icFCe1fNb8RbuwRPqtjUE3Ea5skwpNb",,"error":null,"portNumber":65316}'
2017-08-01 11:31:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0icFCe1fNb8RbuwRPqtjUE3Ea5skwpNb', error: 'null', listeningPort: '65316''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:78615FF3-BB41-476C-AB03-7264399F5297
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65310
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65316
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84056088-3896-48BB-8E52-4509E9BC57C6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:84056088-3896-48BB-8E52-4509E9BC57C6
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DCAE8889-B1C8-4300-B33A-1CA5F88D9114 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "78615FF3-BB41-476C-AB03-7264399F5297", generation: 0)
,[ThaliCore] Session.deinit peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-01 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:31:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:31:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NZW7NXiFtGUPp1fkI5n90HLBXWVMwama","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:84056088-3896-48BB-8E52-4509E9BC57C6
[ThaliCore] Session.deinit peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
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
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:31:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'listening 65320'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89E9158F-D27B-4E2F-96F6-E1F37A89BFDE
,[ThaliCore] Browser.startListening
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:51 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}]'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:31:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'listening 65321'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "17D6D40E-D330-4B38-B1A2-10659A0D4B48", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:17D6D40E-D330-4B38-B1A2-10659A0D4B48
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "17D6D40E-D330-4B38-B1A2-10659A0D4B48", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:17D6D40E-D330-4B38-B1A2-10659A0D4B48
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-01 11:31:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:17D6D40E-D330-4B38-B1A2-10659A0D4B48
,[ThaliCore] Advertiser.stopAdvertising() peerID:17D6D40E-D330-4B38-B1A2-10659A0D4B48
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'listening 65324'
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
2017-08-01 11:31:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:53 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 65325'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D612A43-C433-4041-A8E6-06C9DE046B52
[ThaliCore] Browser.startListening
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandle,r:) Peer(uuid: "2365282A-AE96-49D0-B052-6DB9AE10ADEF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2365282A-AE96-49D0-B052-6DB9AE10ADEF
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}]'
2017-08-01 11:31:54 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2365282A-AE96-49D0-B052-6DB9AE10ADEF
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:31:54 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 65328'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CE282164-04FF-4A95-8D8A-C5CB03A3E2A2
[ThaliCore] Browser.st,artListening
2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A2284492-50B1-4787-8D4C-8F7155C1D987", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:A2284492-50B1-4787-8D4C-8F7155C1D987
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2", generation: 0)
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}]'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","generation":0}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A2284492-50B1-4787-8D4C-8F7155C1D987
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
,2017-08-01 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 65330'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37075CC8-9295-4D29-8851-1EE81F9266BC
[ThaliCore] Browser.startListening
2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5AFB77B2-8609-4F42-B84B-7C0AB2291BBD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5AFB77B2-8609-4F42-B84B-7C0AB2291BBD
2017-08-01 11:31:55 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started",:false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5AFB77B2-8609-4F42-B84B-7C0AB2291BBD
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:31:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-01 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 245 is stopped after calling stop
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
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
,2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-08-01 11:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-01 11:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 65333'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1167F8B6-0923-4C02-9D66-F37D037139C3
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 65334'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3E3FEF44-8AC5-4CA7-9642-A92E880E3424", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3E3FEF44-8AC5-4CA7-9642-A92E880E3424
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3E3FEF44-8AC5-4CA7-9642-A92E880E3424
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 65336'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 65337'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B7F2FA9-1114-45C6-9F9E-41978066A482
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B75A076C-9F54-42F5-AD10-23C35D30B52B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B75A076C-9F54-42F5-AD10-23C35D30B52B
,2017-08-01 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB72E643-E780-49C6-BEC0-4812224ED763:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB72E643-E780-49C6-BEC0-4812224ED763", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:830B4368-4E9E-4860-A257-F1167467DB20:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "830B4368-4E9E-4860-A257-F1167467DB20", generation: 0)
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","generation":0}]'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","generation":0}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","generation":0}]'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","generation":0}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B75A076C-9F54-42F5-AD10-23C35D30B52B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B75A076C-9F54-42F5-AD10-23C35D30B52B", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B75A076C-9F54-42F5-AD10-23C35D30B52B
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:03 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# can do HTTP requests after connections are cut
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 65339'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B30CDCA-9D2B-40A0-9159-6A95AB126B85
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9
,2017-08-01 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-01 11:32:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-01 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
2017-08-01 11:32:05 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A (syncValue: ojyEgm6h42B4uwVDxDZ12EGxpHNU89eE)'
,2017-08-01 11:32:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "41,71E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A434C687-B492-4444-B453-FF485E320B98:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","generation":0}]'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
2017-08-01 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}]'
2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,71E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}]'
2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","generation":0}'
,2017-08-01 11:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-01 11:32:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,71E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-01 11:32:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ojyEgm6h42B4uwVDxDZ12EGxpHNU89eE","error":"Peer is unavailable",,"portNumber":null}'
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ojyEgm6h42B4uwVDxDZ12EGxpHNU89eE', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-01 11:32:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A434C687-B492-4444-B453-FF485E320B98 (syncValue: jJunFUkszpUr89p6pnldi4d,dAwI6jLRm)'
2017-08-01 11:32:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A434C687-B492-4444-B453-FF485,E320B98:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4171E906-2DAC-40F0-BF8A-D6E8BEB2B32A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A434C687-B492-4444-B453-FF485E320B98:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D
[ThaliCore] Advertiser: session connected Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A434C687-B492-4444-B453-FF485E320B98:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A434C687-B492-4444-B453-FF485E320B98:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65347
2017-08-01 11:32:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jJunFUkszpUr89p6pnldi4ddAwI6jLRm",,"error":null,"portNumber":65347}'
2017-08-01 11:32:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jJunFUkszpUr89p6pnldi4ddAwI6jLRm', error: 'null', listeningPort: '65347''
,2017-08-01 11:32:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A434C687-B492-4444-B453-FF485E320B98:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A434C687-B492-4444-B453-FF485E320B98:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 4, 6, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
[ThaliCore] Advertiser: session connected Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307 state: notConnected -> connecting
,2017-08-01 11:32:13 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:13 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D
,[ThaliCore] Session.session(_:peer:didChange:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D
,[ThaliCore] Session.startOutputStream(with:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 4, 6, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
[ThaliCore] Session.startOutputStream(with:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 4, 6, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [1, 4, 6, 15, 16]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] Session.session(_:peer:didChange:) peer:4EB868FD-A513-4CEA-8F7F-4469883FD307 state: connected -> notConnected
[ThaliCo,re] Advertiser: session notConnected Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRe,lay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4EB868FD-A513-4CEA-8F7F-4469883FD307
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B1D3177E-372A-4F29-8F3A-5AC9E326B4C9
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] ,BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] ,AdvertiserManager.stopAdvertising()
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] Virt,ualSocket.closeStreams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 4, 6, 15]
,2017-08-01 11:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A434C687-B492-4444-B453-FF485E320B98
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65347
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A434C687-B492-4444-B453-FF485E320B98:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A434C687-B492-4444-B453-FF485E320B98:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A434C687-B492-4444-B453-FF485E320B98", generation: 0)
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-01 11:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D42D05BC-62A5-44A4-9620-73590AE9409D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B1D3177E-372A-4F29-8F3A-5AC9E326B4C9", generation: 0)
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-01 11:32:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jJunFUkszpUr89p6pnldi4ddAwI6jLRm","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:A434C687-B492-4444-B453-FF485E320B98:0
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5DB0E0CB-D9D6-4C55-8AEE-54C6FEEBC6A2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CB72E643-E780-49C6-BEC0-4812224ED763","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"830B4368-4E9E-4860-A257-F1167467DB20","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A434C687-B492-4444-B453-FF485E320B98","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'listening 65351'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 297 error should be null
ok 298 error shoul,d be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 65352'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BB6B7B9F-93BC-4874-9CE0-BC37C8D9BA6A
,[ThaliCore] Browser.startListening
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
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
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'listening 65353'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5F72EB5-9507-4FEE-86E2-EEC245F20AC5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E5F72EB5-9507-4FEE-86E2-EEC245F20AC5
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 311 error should be null
ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5F72EB5-9507-4FEE-86E2-EEC245F20AC5", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E5F72EB5-9507-4FEE-86E2-EEC245F20AC5
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E5F72EB5-9507-4FEE-86E2-EEC245F20AC5
,[ThaliCore] Advertiser.stopAdvertising() peerID:E5F72EB5-9507-4FEE-86E2-EEC245F20AC5
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-01 11:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-01 11:32:21 - DEBUG thaliMobileNativeWrapper: 'listening 65356'
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
,ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-01 11:32:22 - DEBUG thaliMobileNativeWrapper: 'listening 65357'
,ok 330 first call should succeed
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
,ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72907e0b-6324-466e-a555-207fe64ef104","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
ok 343 should not have been called more than once
,# teardown
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72907e0b-6324-466e-a555-207fe64ef104","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25c59f1e-cfa6-4162-8e36-e1a995d43420","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-08-01 11:32:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25c59f1e-cfa6-4162-8e36-e1a995d43420","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acde0b23-62e0-4682-b1cb-2bbcf7e4ae27","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 360 peer should be available
,ok 361 cache contains wifi peer
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acde0b23-62e0-4682-b1cb-2bbcf7e4ae27","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d45c9ea3-93b2-4550-9955-e1b41bc55b81","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 367 first peer is available
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0650ec11-9a5b-434d-9289-9d2a52c22545","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-08-01 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d45c9ea3-93b2-4550-9955-e1b41bc55b81","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0650ec11-9a5b-434d-9289-9d2a52c22545","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45bc1c87-e1e0-4971-8ceb-c267bd2c8b5a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45bc1c87-e1e0-4971-8ceb-c267bd2c8b5a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-01 11:32:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
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
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57fdfde6-2ea6-4d64-bf60-6828bf98153c","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be available
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57fdfde6-2ea6-4d64-bf60-6828bf98153c","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-08-01 11:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57fdfde6-2ea6-4d64-bf60-6828bf98153c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 65358'
2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76ad1c20-ab8e-4a2c-9455-b0b35e4b8515","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76ad1c20-ab8e-4a2c-9455-b0b35e4b8515","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"76ad1c20-ab8e-4a2c-9455-b0b35e4b8515","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:26 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-08-01 11:32:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-01 11:32:26 - DEBUG thaliMobileNativeWrapper: 'listening 65359'
,2017-08-01 11:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8d6689f5-9b3f-40cf-9a2f-918a06ab575e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered avai,lable peer
ok 398 peer is available
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8d6689f5-9b3f-40cf-9a2f-918a06ab575e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55b6bb48-adcd-4688-8487-07307bd34330","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 402 peer should be available
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"55b6bb48-adcd-4688-8487-07307bd34330","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'listening 65360'
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"006c23f0-d674-4f30-9bb3-162a5a59198c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"379f314a-0734-4e54-b656-811ea587fabd","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"379f314a-0734-4e54-b656-811ea587fabd","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"379f314a-0734-4e54-b656-811ea587fabd","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 412 we found peer again
ok 413 it was wifi peer
2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"379f314a-0734-4e54-b656-811ea587fabd","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-08-01 11:32:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"006c23f0-d674-4f30-9bb3-162a5a59198c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-08-01 11:32:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
ok 417 error should be null
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
,2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'listening 65361'
2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97e5b499-f8bb-4e94-9840-5ad633676a64","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2995724b-6285-4970-87ed-51e0e8dc11e9","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97e5b499-f8bb-4e94-9840-5ad633676a64","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 424 pee,r became unavailable
2017-08-01 11:32:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2995724b-6285-4970-87ed-51e0e8dc11e9","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-01 11:32:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
ok 427 error should be null
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
,ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7fb493cd-95df-410d-b1df-bb8255ccb3ce","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7fb493cd-95df-410d-b1df-bb8255ccb3ce","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7fb493cd-95df-410d-b1df-bb8255ccb3ce","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 437 new port handled correctly
,2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7fb493cd-95df-410d-b1df-bb8255ccb3ce","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled, correctly
2017-08-01 11:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7fb493cd-95df-410d-b1df-bb8255ccb3ce","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 new,AddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
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
ok 451 error should be null
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
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-08-01 11:32:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 65362'
2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c081c4d7-88c8-4870-9cfa-0e2d6f34946a","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 472 Got specific error message
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c081c4d7-88c8-4870-9cfa-0e2d6f34946a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-08-01 11:32:32 - DEBUG thaliMobileNativeWrapper: 'listening 65363'
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9171c9e9-dd47-461b-bd2f-6389e2169feb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:9171c9e9-dd47-461b-bd2f-6389e2169feb
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-01 11:32:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9171c9e9-dd47-461b-bd2f-6389e2169feb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 491 error should be null
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
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'listening 65364'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E73BBF0F-B0C5-4A48-B3BD-6A5580157634
[ThaliCore] Browser.startListening
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57c452ac-e167-4a19-90f9-6b3971b02d90","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46705efd-96c1-45aa-a6e9-05427fd8406d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57c452ac-e167-4a19-90f9-6b3971b02d90","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"46705efd-96c1-45aa-a6e9-05427fd8406d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'listening 65365'
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d3f1838c-0d3b-42a0-aa60-36f2009c418e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 1
,ok 511 2
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8c96cf86-3006-44e6-97b7-34a075a11297","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-01 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d3f1838c-0d3b-42a0-aa60-36f2009c418e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8c96cf86-3006-44e6-97b7-34a075a11297","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-01 11:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-01 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
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
,2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'listening 65366'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7D,C1227E0497", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FF233C22-60DB-4B1D-B6ED-7DC1227E0497
2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B3DD96E-12C8-4FCA-BDE1-1CB5D3E46207
[ThaliCore] Browser.startListening
2017-08-01 11:32:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-45,3E-BBDF-6FB61274F5F5","generation":0}]'
2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}'
2017-08-01 11:32:3,7 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","generation":0}]'
2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Received ,peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","generation":0}'
,2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7EDC3305-B405-453E-BBDF-6FB61274F5F5 (syncValue: 0)'
,2017-08-01 11:32:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FF233C22-60DB-4B1D-B6ED-7DC1227E0497:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","generation":0}]'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","generation":0}'
,2017-08-01 11:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:32:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] Advertiser: session connected Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,DC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
,[ThaliCore] Session.session(_:peer:didChange:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] Session.startOutputStream(with:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [1, 4, 6, 15, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,DC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Advertiser: session connected Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(d,idReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3CE935A7-111C-47D8-8125-279181E75889 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EDC3305-B405-453E-BBDF-6FB612,74F5F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CE935A7-111C-47D8-8125-279181E75889 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,DC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 4, 6, 15, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,DC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7EDC3305,-B405-453E-BBDF-6FB61274F5F5 error: max retries exceeded
2017-08-01 11:32:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-08-01 11:32:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for ACA77010-5D8E-4A90-81AB-BDF0C37999E5 (syncValue: 1)'
2017-08-01 11:32:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7EDC3305-B405-453E-BBDF-6FB61274F5F5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7EDC3305-B405-453E-BBDF-6FB61274F5F5", generation: 0)
2017-08-01 11:32:50 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}]'
2017-08-01 11:32:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","generation":0}'
,2017-08-01 11:32:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-01 11:32:50 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"7EDC3305-B405-453E-BBDF-6FB61274F5F5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65380
,2017-08-01 11:32:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":65380}'
,2017-08-01 11:32:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CA88F631-A53F-4016-997C-EACC85DE23E5 (syncValue: 2)'
,2017-08-01 11:32:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 4, 6, 15, 18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:32:51 - DEBUG testUtils: 'Got response data'
,2017-08-01 11:32:51 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65384
,2017-08-01 11:32:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":65384}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 4, 6, 15, 18, 19, 20, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsH,andler
,2017-08-01 11:32:55 - DEBUG testUtils: 'Got response data'
2017-08-01 11:32:55 - DEBUG testUtils: 'Got end'
ok 524 received all uuids
,# teardown
,2017-08-01 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ACA77010-5D8E-4A90-81AB-BDF0C37999E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-01 11:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CA88F631-A53F-4016-997C-EACC85DE23E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FF233C22-60DB-4B1D-B6ED-7DC1227E0497
2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingA,ctive":false}'
2017-08-01 11:32:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017,-08-01 11:32:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-01 11:32:55 - DEBUG thaliMobileNativeWrap,p,er: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [1, 4, 6, 15, 18, 19, 20]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ac,cepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:32:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeS,treams() vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] V,irtualSocket.closeStreams() vsID:19
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 4, 6, 15, 19, 20]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [1, 4, 6, 15, 20]
,ok 525 error should be null
,ok 526 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 4, 6, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket ,removed, count:0
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
ok 553 Entry counter must be 1
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
ok 566 Entry 2_1 should not be found
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
,ok 584 enqueue is fine
,ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 591 Queue is empty
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
,ok 599 is an agent
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
ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
,ok 610 wrong arg type
,ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
,ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
ok 618 Action was killed
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
ok 665 First does, not throw
,2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 666 is an agent
ok 667 Second does not throw
2017-08-01 11:33:10 - DEBUG thaliPeerPoolOneAtATime: 'action, returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
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
,ok 680 Once start returns the action should be in KILLED state
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
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
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
# teardown
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
,ok 718 should be equal
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
ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
ok 733 keys match
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
2017-08-01 11:33:29 - WARN thaliNotificationClient: 'peer is not available'
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
,ok 758 connectionType must match
,ok 759 peerIds must match
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
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
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
ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-08-01 11:33:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-08-01 11:33:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
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
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
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
,ok 808 First start and on called correctly
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
2017-08-01 11:34:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-08-01 11:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-08-01 11:34:10 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-01 11:34:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-08-01 11:34:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-08-01 11:34:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
ok 859 Error should be timed out
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
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'listening 65511'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B271DA44-A576-46BE-9CB5-E4002F1E015B
[ThaliCore] Browser.startListening
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1
,2017-08-01 11:34:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 3)'
,2017-08-01 11:34:16 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Advertiser: session connected Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}]'
2017-08-01 11:34:17 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}'
,2017-08-01 11:34:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65515
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":65515}'
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 4)'
,2017-08-01 11:34:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 4, 6, 15, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 4, 6, 15, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Advertiser: session connected Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 4, 6, 15, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 4, 6, 15, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 4, 6, 15, 22, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 4, 6, 15, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 6146043904:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
'
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: 6146043904:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [1, 4, 6, 15, 22, 23, 24, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [1, 4, 6, 15, 22, 23, 24, 27, 28, 29, 30, 31, 32]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [1, 4, 6, 15, 22, 23, 24, 27, 29, 30, 31, 32]
,2017-08-01 11:34:20 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-08-01 11:34:20 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 4, 6, 15, 22, 23, 24, 27, 29, 30, 31]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] Session.session(_:peer:didChange:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 34]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:65531
,2017-08-01 11:34:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":65531}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 34, 35]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 35]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 35, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 35, 37, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 35, 37]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 37, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) pee,r:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 37, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 4, 6, 15, 22, 23, ,24, 27, 29, 31, 37, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:41
,[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.handleEventOnOutputStream streams are closed vsID:41
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:41 [1, 4, 6, 15, 22, 23, 24, 27, 29, 31, 37, 39, 40]
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[Thali,Core] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [1, 4, 6, 15, 22, 23, 27, 29, 31, 37, 39, 40]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 4, 6, 15, 22, 23, 29, 31, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socket,DidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDiscon,nect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 4, 6, 15, 22, 23, 31, 37, 39, 40]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 4, 6, 15, 22, 23, 37, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisco,nnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-01 11:34:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42, 43]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42, 43, 44]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 4, 6, 15, 22, 23, 37, 39, 40, 42, 43, 44, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] VirtualSocket exited RunLoop vsID:,37
[ThaliCore] VirtualSocket.deinit vsID:37 [1, 4, 6, 15, 22, 23, 39, 40, 42, 43, 44, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconn,ected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 4, 6, 15, 22, 23, 39, 42, 43, 44, 46]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 4, 6, 15, 22, 23, 39, 42, 44, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [1, 4, 6, 15, 22, 23, 42, 44, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [1, 4, 6, 15, 22, 23, 44, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [1, 4, 6, 15, 22, 23, 46]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 4, 6, 15, 22, 23, 46, 47]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-08-01 11:34:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,2017-08-01 11:34:24 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E07BFCF8-CD88-4962-AAA9-802C74BFD5C1
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-01, 11:34:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-01 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-01 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-01 11:34:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:46
,[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:46 [1, 4, 6, 15, 22, 23, 47]
,ok 865 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [1, 4, 6, 15, 22, 23]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 4, 6, 15, 22, 23, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,9 [1, 4, 6, 15, 22, 23, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo,={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual soc,ket vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [1, 4, 6, 15, 22, 23, 49]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'listening 49163'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:11ECE8FB-239A-4449-806D-FE40ECE6AF8D
,[ThaliCore] Browser.startListening
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "68F79609-0A85-42F9-884E-51FBAC4E0541", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:68F79609-0A85-42F9-884E-51FBAC4E0541
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}]'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}]'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","generation":0}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94315540-88C1-4914-B493-B105D908F8AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-01 11:34:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3C03286D-92EB-4924-A2C4-E042DE28FC9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 5)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":65515}'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 6)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":65531}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 4, 6, 15, 22, 23, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 4, 6, 15, 22, 23, 49, 50, 51]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 4, 6, 15, 22, 23, 49, 50, 51, 52]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [1, 4, 6, 15, 22, 23, 49, 50, 52]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [1, 4, 6, 15, 22, 23, 49, 50]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 4, 6, 15, 22, 23, 49, 50, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [1, 4, 6, 15, 22, 23, 49, 50]
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 4, 6, 15, 22, 23, 49, 50, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:54
,[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [1, 4, 6, 15, 22, 23, 49, 50]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 7)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":65515}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 8)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":65531}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 4, 6, 15, 22, 23, 49, 50, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[Th,aliCore] VirtualSocket.deinit vsID:55 [1, 4, 6, 15, 22, 23, 49, 50]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Browser,Relay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [1, 4, 6, 15, 22, 23, 49, 50, 56]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStre,amsHandler
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 4, 6, 15, 22, 23, 49, 50]
,2017-08-01 11:34:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 4, 6, 15, 22, 23, 49, 50, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [1, 4, 6, 15, 22, 23, 49, 50]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] Session.startOutputStream(with:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 4, 6, 15, 22, 23, 49, 50, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [1, 4, 6, 15, 22, 23, 49, 50]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3CE935A7-111C-47D8-8125-279181E75889
[ThaliCore] Session.startOutputStream(with:) peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [1, 4, 6, 15, 22, 23, 49, 50, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [1, 4, 6, 15, 22, 23, 49, 50]
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 9)'
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":65515}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 10)'
,2017-08-01 11:34:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) found active relay
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":65531}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [1, 4, 6, 15, 22, 23, 49, 50, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 4, 6, 15, 22, 23, 49, 50, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.handleEventOnInputStream en,dEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [1, 4, 6, 15, 22, 23, 49, 50, 60]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) ,accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] Vir,tualSocket exited RunLoop vsID:60
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:60 [1, 4, 6, 15, 22, 23, 49, 50]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket, removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-01 11:34:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 94315540-88C1-4914-B493-B105D908F8AF (syncValue: 11)'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0) found active relay
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":65515}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94315540-88C1-4914-B493-B105D908F8AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 4, 6, 15, 22, 23, 49, 50, 62]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStre,amsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [1, 4, 6, 15, 22, 23, 49, 50]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Brow,serRelay.didSocketDisconnectHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
2017-08-01 11:34:27 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:65531
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
[ThaliCore] TCPListener.deinit
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3C03286D-92EB-4924-A2C4-E042DE28FC9F (syncValue: 12)'
,2017-08-01 11:34:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.deinit peer:3C03286D-92EB-4924-A2C4-E042DE28FC9F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3C03286D-92EB-4924-A2C4-E042DE28FC9F", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CE935A7-111C-47D8-8125-279181E75889 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3CE935A7-111C-47D8-8125-279181E75889
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] Session.startOutputStream(with:) peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,3 [1, 4, 6, 15, 22, 23, 49, 50, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C01422D0-A999-486C-9896-7E773FFB2A7E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected ,Peer(uuid: "E07BFCF8-CD88-4962-AAA9-802C74BFD5C1", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() pee,r:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
[ThaliCore] TCPClient.deinit
[ThaliCore] Session.deinit peer:67DF26D7-0391-46BF-9A8E-7C486EF20B1D
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:94315540-88C1-4914-B493-B105D908F8AF:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:65515
[ThaliCore] Session.disconnect() peer:94315540-88C1-4914-B493-B105D908F8AF:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "94315540-88C1-4914-B493-B105D908F8AF", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AABEB37E-ECB2-488B-8C56-59E412028A74 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FF233C22-60DB-4B1D-B6ED-7DC1227E0497", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:65384
[ThaliCore] Session.disconnect() peer:CA88F631-A53F-4016-997C-EACC85DE23E5:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "CA88F631-A53F-4016-997C-EACC85DE23E5", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:65380
[ThaliCore] Session.disconnect() peer:ACA77010-5D8E-4A90-81AB-BDF0C37999E5:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "ACA77010-5D8E-4A90-81AB-BDF0C37999E5", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit

```
