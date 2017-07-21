#### Test 113351851d000154_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/353A9FFA-8E16-4089-8A2D-DAE476EEB18D/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/353A9FFA-8E16-4089-8A2D-DAE476EEB18D/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57396"
,(lldb)     command script import "/tmp/353A9FFA-8E16-4089-8A2D-DAE476EEB18D/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
(lldb)     connect
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
,2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:54:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8AF66DBF-6A30-49F0-8A55-8DE008513F61", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8AF66DBF-6A30-49F0-8A55-8DE008513F61
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC31E37C-B4FA-4A97-B41B-84621B3B779F
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:817111CA-,EE45-4EF0-83DF-091DDD13C243
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D7E924D-870C-455D-852D-E5CE91E3409B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D7E924D-870C-455D-852D-E5CE91E3409B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7E924D-870C-455D-852D-E5CE91E3409B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7E924D-870C-455D-852D-E5CE91E3409B", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-21 07:54:16 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of fail,ed tests:  0
Number of ignored tests:  0
Total duration:  1.47705602645874
,2017-07-21 07:54:16 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-21 07:54:16 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D7E924D-870C-455D-852D-E5CE91E3409B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D7E924D-870C-455D-852D-E5CE91E3409B", generation: 0)
,2017-07-21 07:54:17 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 07:54:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 07:54:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 07:54:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 07:54:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 07:54:19 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 07:54:20 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 07:56:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 07:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 07:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
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
# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
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
# teardown
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
,ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
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
,ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
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
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6E9EAD81-B6E9-47E5-A0A1-7D81005259D7
[ThaliCore] Browser.startListening
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0A603796-A453-4E8F-BCC9-CECB340915FD
[ThaliCore] Browser.startListening
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:44 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "55947880-63AF-4292-884B-A1E4BCD71DF9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:55947880-63AF-4292-884B-A1E4BCD71DF9
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:55947880-63AF-4292-884B-A1E4BCD71DF9
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "94156172-0FAC-4A19-BC60-52A00BF391ED", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:94156172-0FAC-4A19-BC60-52A00BF391ED
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "94156172-0FAC-4A19-BC60-52A00BF391ED", generation: 1)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:94156172-0FAC-4A19-BC60-52A00BF391ED
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:5,6:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:94156172-0FAC-4A19-BC60-52A00BF391ED
[ThaliCore] Advertiser.s,topAdvertising() peerID:94156172-0FAC-4A19-BC60-52A00BF391ED
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:47 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:47 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:56:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:497CA652-F546-4F78-A215-E1AFC9EE5C1C
[ThaliCore] Browser.startListening
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C21BA560-FF4E-445D-9B31-8D16DD9BA945:0
ok 76 peers must be an array
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C21BA560-FF4E-445D-9B31-8D16DD9BA945", generation: 0),
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:56:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CD6697C3-80A5-4BF6-8ACF-D,DFD13E1FBCF
2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:26D99AE4-FD01-4D89-8824-8246C4432DC5
2017-07-21 0,7:56:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:862E2617-8FB6-4A3C-A4F3-3A422747726D
[Thal,i,Core] Browser.startListening
2017-07-21 07:56:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:50 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6F4D58C6-50EC-4889-A6E2-79C7E140AF34","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6F4D58C6-50EC-4889-A6E2-79C7E140AF34 (syncValue: jEMRgD2GiX441UOPKYIFrAdPghcNZLXs)'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B379,89","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:56:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit, ,peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6F,4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:56:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jEMRgD2GiX441UOPKYIFrAdPghcNZLXs","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:56:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jEMRgD2GiX441UOPKYIFrAdPghcNZLXs', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:56:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"6F4D58C6-50EC-4889-A6E2-79C7E140AF34","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:56:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:56:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6F4D58C6-50EC-4889-A6E2-79C7E140AF34","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:56:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:56:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:56:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DB06BF0-3361-4720-9B4B-E8F6A5B37989 (syncValue: jKwmtNZPeLNplJWIfklqzVq,Q6aBxkXvU)'
2017-07-21 07:56:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DB06BF0-3361-4720-9B4B-E8F6A,5B37989:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:56:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6F4D58C6-50EC-4889-A6E2-79C7E140AF34:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55858
2017-07-21 07:57:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jKwmtNZPeLNplJWIfklqzVqQ6aBxkXvU","error":null,"portN,umber":55858}'
2017-07-21 07:57:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jKwmtNZPeLNplJWIfklqzVqQ6aBxkXvU', error: 'null', listeningPort: '55858''
,2017-07-21 07:57:01 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 07:57:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:26D99AE4-FD01-4D89-8824-8246C4432DC5
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55858
[ThaliCore] Session.disconnect,() peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jKwmtNZPeLNplJWIfklqzVqQ6aBxkXvU","error":"Session disconnected","portNumber":null}'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:44B8682C-03C2-4208-8FBD-AE9D3CBB179E
2017-07-21 07:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:05, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45
[ThaliCore] Browser.startListening
2017-07-21 07:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-21 07:57:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","generation":0}'
[T,haliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
2017-07-21 07:57:06 - DEBUG tha,liMobileNativeTestUtils: 'Issuing multiConnect for 1DB06BF0-3361-4720-9B4B-E8F6A5B37989 (syncValue: 97mEOxdRQyc6JXd2aabZQCNfTw22R0aF)'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3297E131-DDDB-48D9-8747-F6AA1CD08F8F","generation":0}'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
2017-07-21 07:57:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","generation":0}'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1D,B06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"97mEOxdRQyc6JXd2aabZQCNfTw22R0aF","error":"Peer is unavailable","portNumber":null}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '97mEOxdRQyc6JXd2aabZQCNfTw22R0aF', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22B764CD-1CCE-4DBA-91F5-A067A3B0164D (syncValue: fBz39DFBOZqTUxrOJNygfyQ,nUjNemgbc)'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22B764CD-1CCE-4DBA-91F5-A067A,3B0164D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,7:57:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.deinit
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
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
[ThaliCore] Advertiser: session connected Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
[ThaliCore] Session.startOutputStream(with:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Server data flushed'
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:22,B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:22B764CD,-1CCE-4DBA-91F5-A067A3B0164D error: max retries exceeded
2017-07-21 07:57:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fBz39DFBOZqTUxrOJNygfyQnUjNemgbc","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:57:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fBz39DFBOZqTUxrOJNygfyQnUjNemgbc', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:57:22 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 07:57:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"22B764CD-1CCE-4DBA-91F5-A067A3B0164D","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:57:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:57:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3297E131-DDDB-48D9-8747-F6AA1CD08F8F (syncValue: oaHKAuj,Nx7nDvkt2nGpCSlzIkg5a3uMK)'
2017-07-21 07:57:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3297E131-DDDB,-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:57:22 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-21 07:57:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55871
2017-07-21 07:57:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oaHKAujNx7nDvkt2nGpCSlzIkg5a3uMK",,"error":null,"portNumber":55871}'
2017-07-21 07:57:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oaHKAujNx7nDvkt2nGpCSlzIkg5a3uMK', error: 'null', listeningPort: '55871''
,Connecting to the localhost:55871
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
,Connected to the localhost:55871
2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,2017-07-21 07:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:44B8682C-03C2-4208-8FBD-AE9D3CBB179E
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55871
[ThaliCore] Session.disconnect() p,eer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
,[ThaliCore] Session.deinit peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:57:27 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:950874DD-50F5-4754-B6B8-316A63E92A54
,2017-07-21 07:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C,12AC
[ThaliCore] Browser.startListening
2017-07-21 07:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","generation":0}'
,2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 387EC95F-5F42-4F46-A25B-FFFA6275C91A (syncValue: hhStAUnJjEdW0cX5cHcPTvSvxxOn5eUD)'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3297E131-DDDB-48D9-8747-F6AA1CD08F8F","generation":0}'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
2017-07-21 07:57:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","generation":0}'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:29 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C67E6215-DEE9-4444-A445-F329D8DE911F","generatio,n,":0}'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,7EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,87EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,7EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,87EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,7EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,87EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,7EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:387EC95F,-5F42-4F46-A25B-FFFA6275C91A error: max retries exceeded
2017-07-21 07:57:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hhStAUnJjEdW0cX5cHcPTvSvxxOn5eUD","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:57:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hhStAUnJjEdW0cX5cHcPTvSvxxOn5eUD', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:57:39 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 07:57:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:57:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:57:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18629558-6C03-4C79-916D-F3DF313B891E (syncValue: tgAJFa1,cOUwBeDqjoV08xAB6B5Wf4sG6)'
2017-07-21 07:57:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18629558-6C03,-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:57:39 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 07:57:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55887
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tgAJFa1cOUwBeDqjoV08xAB6B5Wf4sG6","error":null,"portNumber":55887}'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tgAJFa1cOUwBeDqjoV08xAB6B5Wf4sG6', error: 'null', listeningPort: '55887''
,Connecting to the localhost:55887
,Connecting to the localhost:55887
,Connecting to the localhost:55887
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,Connected to the localhost:55887
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:55887
,[ThaliCore] Session.startOutputStream(with:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,Connected to the localhost:55887
,ok 91 correct string length
,2017-07-21 07:57:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 07:57:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-,4C79-916D-F3DF313B891E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18629558-6C03-4C79-916D-F3DF31,3B891E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5]
,2017-07-21 07:57:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:950874DD-50F5-4754-B6B8-316A63E92A54
2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:18629558-6C03-4C79-916D-F3DF313B891E
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55887
[ThaliCore] Session.disconnect() peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B84EE5A7-220B-4B6A-9E36-00A6615627EF
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57A5A079-6D1E-476E-9F1D-C726B6B16C4F
[ThaliCore] Browser.startListe,ning
2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
2017-07-21 07:57:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","generation":0}'
2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18629558-6C03-4C79-916D-F3DF313B891E, (syncValue: nnVhkE3LrfzqAU8VC0vaPQQdYRB09UmJ)'
2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313,B891E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","generation":0}'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","generation":0}'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
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
[ThaliCore] BrowserRelay.deinit
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:18629558-6C03-4C79-916D-F3DF313B891E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:18629558,-6C03-4C79-916D-F3DF313B891E error: max retries exceeded
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nnVhkE3LrfzqAU8VC0vaPQQdYRB09UmJ","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nnVhkE3LrfzqAU8VC0vaPQQdYRB09UmJ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"18629558-6C03-4C79-916D-F3DF313B891E","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 07:58:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB (syncValue: 4lQpPJL,jntrEtYJQLKZRmwoFnjz7Xutu)'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9DB02CB4-9A8D,-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 07:58:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9E590909-86C7-473F-832E-5B73F900B018
[ThaliCore] Advertiser: session connected Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9E590909-86C7-473F-832E-5B73F900B018 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:18629558-6C03-4C79-916D-F3DF313B891E:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9E590909-86C7-473F-832E-5B73F900B018
,[ThaliCore] Session.session(_:peer:didChange:) peer:9E590909-86C7-473F-832E-5B73F900B018 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0 state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55904
2017,-07-21 07:58:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4lQpPJLjntrEtYJQLKZRmwoFnjz7Xutu","error":null,"portNumber":55904}'
2017-07-21 07:58:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4lQpP,JLjntrEtYJQLKZRmwoFnjz7Xutu', error: 'null', listeningPort: '55904''
,Connecting to the localhost:55904
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9E590909-86C7-473F-832E-5B73F900B018
[ThaliCore] Session.startOutputStream(with:) peer:9E590909-86C7-473F-832E-5B73F900B018
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,Connected to the localhost:55904
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:58:10 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeSt,reams() vsID:7
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
ok 99 got the same data back
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [5]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050
[ThaliCore] Advertiser: session connected Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050
,[ThaliCore] Session.session(_:peer:didChange:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050 state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050
[ThaliCore] Session.startOutput,Stream(with:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [5, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [5]
,2017-07-21 07:58:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B84EE5A7-220B-4B6A-9E36-00A6615627EF
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55904
[ThaliCore] Session.disconnect,() peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9E590909-86C7-473F-832E-5B73F900B018 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E092C709-FCA2-4A63-AB10-BBD04D919050
,[ThaliCore] Session.deinit peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:E092C709-FCA2-4A63-AB10-BBD04D919050
[ThaliCore] AdvertiserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C
,2017-07-21 07:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6,F4535
[ThaliCore] Browser.startListening
2017-07-21 07:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:58:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
2017-07-21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","generation":0}'
,2017-07-21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB (syncValue: 3lRSxPE543p60ZZJTNt9mvHXTv2LRr5t)'
2017-07-21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB0,2CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","generation":0}'
2017-07-21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,21 07:58:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
2017-07-21 07:58:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,B02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:58:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3lRSxPE543p60ZZJTNt9mvHXTv2LRr5t","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:58:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3lRSxPE543p60ZZJTNt9mvHXTv2LRr5t', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:58:23 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:58:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:58:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:58:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 25BA6BBB-1122-4518-BE28-A26BE6496CE8 (syncValue: wDgyBLKT4oALgQXuVtPNmMI,Z6oCOjeV3)'
2017-07-21 07:58:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25BA6BBB-1122-4518-BE28-A26BE,6496CE8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:58:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,7:58:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:70B04368-0D4A-4A8D-9826-F72B55687508
[ThaliCore] Advertiser: session connected Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:70B04368-0D4A-4A8D-9826-F72B55687508 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:25,BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,5BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:58:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wDgyBLKT4oALgQXuVtPNmMIZ6oCOjeV3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:58:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wDgyBLKT4oALgQXuVtPNmMIZ6oCOjeV3', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:58:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:58:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"25BA6BBB-1122-4518-BE28-A26BE6496CE8","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:58:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:58:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45972DD7-E306-4909-AA0D-0C667C726D62 (syncValue: CK5z84RBgZLoTM4cJWtD4mxwisuzfseR)'
2017-07-21 07:58:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45972DD7-E306-4909-AA0D-0C667,C726D62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:58:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
[ThaliCore] Advertiser: session connected Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:70B04368-0D4A-4A8D-9826-F72B55687508
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55918
,2017-07-21 07:58:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CK5z84RBgZLoTM4cJWtD4mxwisuzfseR","error":null,"portNumber":55918}'
,2017-07-21 07:58:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CK5z84RBgZLoTM4cJWtD4mxwisuzfseR', error: 'null', listeningPort: '55918''
,Connecting to the localhost:55918
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
,Connected to the localhost:55918
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [5, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:70B04368-0D4A-4A8D-9826-F72B55687508 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:70B04368-0D4A-4A8D-9826-F72B55687508
[ThaliCore] Session.startOutputStream(with:) peer:70B04368-0D4A-4A8D-9826-F72B55687508
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [5, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received (65536 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received all data: tlkCACK1TpFp8sdZ0J9BYcN4Ylb3JPP2waLGKaaf0i5aM92DKOUtidgjdLeERMFvJ5ZK5BUhLh8AnJlrgDaq19KYT8vZ9Ftw3qb9NZ8IlRc0QXznEyyH0pZOaNg8avdgsZRMNkSuBjUQyxw6FWwbn32v2R6M4UFC0O1N8vnifUBQgSCAHl,bDIxNUn6wlMixemAlG0c3KT2J4b00BBQaWSI7E3Bbnfa3ru8QhwFisx8c0KUnTgP6jnLF1WEerlzCTiffFjsVeM7pDAVK02bFJnvxmFtCGC4w6jJZHkhfTRyYt7gQmUP8bw6j8DzxZypmfT62Epv995X1VdlPW2zJxLGlBmQbBytNs1MDymru6A02WlklnFkwRdlK5pzWAEl2JwxxgC1jRD3FtoWwimrgL3YIKS6Qdbqfa9pmBrNEYZwxKDDWR8N,uU9r2KZC38WVP7VrNHu3fcay4lpv7hlub9m4C6JfQsOtKxIJvbMP0mnloTPnQSmrGKuatWmoBNH417JwFcuykziUZd9Zqf7MnexcLGKikvIDqCrlzX8RNfN3okN83JEveCOPpw4ItsVNRQVkJSOjBvEOItm9uw44KjlOAtsK7cP3BMfDMIpDqn1FfB0logo8P48InnspvvcXJODVCd7dA5FHjGviPTdg6jtXFkdrpEAMJYYxQI2YdynwuU828RCG,LuPJpV7W92Ta9AJos7GgoNoiEbvU1ReWTBmTs6CANSzBLufCnwvqkwZShxxVjXj6w59M1NKQPGyNbpUKccoKX8WS6zokvBTj798nVjVDy9XFDLNStmChIFUCCiVVsTfzYWjFPJqdakuq7qTzKhld1jyDwHqYSdZCpYjk8ijYkg52KZTTYEWAbCdBPTdw7cxsxNdxmysnBdsRIAanRJBxsYJpLaPabyAr7OJzIjKn6HuwuJBkWYSQxD9SoyYobthv,hLCAYKFlsbnJZtW8lR0PY3XMDE2RMZjkkWgYaGLxQGVXE2Q823C6wH5FToJJYLlIJGu2viGtY6I7FzkGtkfbscuqkyQZpZF4qqEEnLBm80KiKh5YYTjd7KjnZ2BrtV94UE5TCZkoGzhl6QTOY3Lt51p51Fg5H75J0nGBiMWfptKJz6jSCZiHKhoc4RZ12klmd5aibHG3OFVv6ei8uqSrSlzeDXy1ZsLX5yoEEie3Z8zhfO1WUq7eFwPqDZYgylFX,l34ukHgrIvLfntMi1VXuMvCnOn5eboMWiAl1ryaVALfmkyS6nWX2hVplExd5lrITImUkKDMCIbOibIrzBcqQsO8IoA4Pwl61dHw8rZheoxzRWBqBWuwZu6Olo35rqisXpv1XpWhpjZzLYM5jQGBOftAYZWsHMN7KxElmHQhEJ16yJFRWzTdBafhv8k5AfsCrXh4vYY73P6CIyDrRAzNy8rlLTAHPu6iuXBqPaqPPVHCNnlZj6Kw0LcGCBRmmhFtQGjhAO6DWJrehQwBpwocYx5iOs5XfVouxswnW5CDk04xYMRDy4Onp4Kp2lWgUOB9l4j6pLtIbZ28w2h2kcyz6zyzZVP1LIac8cvdeq3ro8P6j8dwiMKLWs5gr0LgUnCxyvNCoqrAt0BjR63OtbuBm5gxNSNoLEh9CV48a1v1b1ttSTooRXc6TseLOyaWgVicMYQQayuFBHOQaQuyRw9lLak3J9Gq1DQnpV327yNykfARFhQme8Ytc1QG8AqA6Lm3A,bDPF1WLvaJb8goYugDnbjqRv8wLa8rHgWXYZZDaCcHzWymxH37sJoy1Z7NkZwivFPMNXsFXBsUDw2jYm5RJNHNy3T1IfS1aJQmpCzSld53fUXFEMfFRvh86nAqBjAi8G7su5xxsZ25DZtfdBnYP277bXSuMuIbYVMDnftaYCjbKBanInEW6LwAhhXwRtofciW7rAnlgOmsJybNilr68EhSY8bxaExvQuNvXJi4xe2ZNod0e5nTO8yf6InjNeaSK,Z,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,a,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,H,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,j,6SX0Lwc7MSEOhKwH8ChflSlzTWUeUME2eBM9H2AtnJUJyz40cPnSgDNayPxhfPIjgEcZKEW9btQv2UQn4LZCvvcTNjicSlc6DdV5ybbav1cXo1Bwo5SlNL4i9RwVLL6mhz51aM9ej9lebxXytg2CM5IxIoiSLlyuRpkMu6MxKwvElo1rtbmUHX4uspXNLpHqwPtKeykDI0AviBEUoGgPnqondcPGl0nMLKcuK4oA7lcSoIPqZU5WX1BsEtbgWGb3,aEiFqB3Ns4CvuDeze18oHKq6bM6nxgZmYQHXKYIm8Q0Vwo0nTGIaJvmfEtQivgpmz7nQBn7njSLpSXT41vo9UWaqzZgs7ufV7OCd5t3H1Kxh9L4xoNmSASg8obMebUVHykdufSQZPdnnMoTcehelQ5Ga0HledeZ8h0pKpheypA47zRX1MrXg3twB14T0C3zfva3ty46Gm4kETpFD5Q5CBsDVhSLK77GbydcWCLp1yjcEiburjpU1po7kRRrywHUt,F3QTYNXhOHQXTaHVh9zK8Ft17msnAJA4PSimfnX0a4ql9dgsXLsjn1FtjLibxOQNboENj9RGGchzh476gTws8caKvhcTWKGshMHiHirBohmw8DJbM7Taatbjia1wwQpaieIy7SnWZ8UmwSovAt7im5DbRPANbMUy1pTSHbEQqBXJoekts1XbYIFmdTTqFToWsITH8gmd6RHnd0eSJQtDWD8Ah38FbGX1aWKxXiZ6pdjSeywHZYZ3b709SsqBBdvJ,j7CwOR82WqPRwqhKnNM1VN67vKE0Ju3MF6k9M9O3HR3h4TeKEmLJsmyXPX0dXfKqry0A31ICXZ1QOjNnCXzAwmSaqnTfoF9HgoenwRxg6c2bYZCgLlnFwfQTSIZAvHLA8JHbdEBrXvspxAgZbF7wchdzf56RNYFHdSt6OayXs3QWdgWSZd6bcR1eZ3KRdZoxPzfUTX4rCc5kqRVwH2aOMERzSwU0DESDu4LJzRHgmJ6ST3hBxyaP1tKqwVHSyJwq,fESV5eRBJmM3y9rmlUbOqYCxbz8lnac3YrlveFiCXLLe6KIQyuwC5JqvdVtl7O4E9oEtsbX1XgKmAEEe7YAuqNP6tDSldmMiBSDa2bIjvAKKVVOYDdvIN1LRx2LUpD6rw43mEQ1j0eqYCFZO9k48EfkU8rX8sbOuAlIV5O7Q2pxsp2SuKiowAUTOR8VgbxHgtoFi7fythGUpxKFaxWW2dTZJuFxT4d4o2TdsmHhBnkX3NZrEFv3vDvQkVjHmcF2s,wmwNCC6EtFFKZbcfQjF7cOTT1A7fgjxN9WyqyIG9SoVL7FLbkpMD0s3FgjrZgZSRluLyDW08helbtGRUvk669PmWnyTQOPsXV3SHALP6JasEFRvqX3ucsi9B4y5Sd9eak0eSAa6gg1W8nUHfZGyJKdOXLZeLUhfVvvMkqYbB3kuvVk9fIsvbbxnx3u08z17YWiiPqTnPGYFLnR7MrfW0zB6huykRPtJjV4f3PrlDnsyZLz5IaX05Bleezh1KgBRY,0a3XLmskrhGE8jfGQeS3tzqahXKzVt5YrxsvZkNMlAnbZSD6g23rzK69cxXykOCXoCoabMbgxGwGQb2t46jR1ZAlJOJLQrMbxOGsQtfE6zpebiKQwkA0ZCBZ5CpKW4p9YOeRg03eX8GGOyAD0OjuCn4tIWoXFZS9IoWOnGPFbn8vNnC6PqKNecbz0CMCKldu2PVrPncTG3L63PIbFUB5hDa36dv9ClMNztzMM62lHtbfDGLU59KXSt4b9IDhVYup,k8dsjKikGdzvxy2ZrLi8ZOBAPrFxx5F0ZHAByPBdyJdGnm2IqISY0uYM5DJDKUgsDtTyZ0T3Ifr6EDRZKkl9hKP4r6jWZozITiTjTsC5X8kYBjT4L7vngIdhfjT3ejdl6Rf8NEVWTGkTIawSVaFaQqr4S1J2feCQvCpOGs0qibcziaVS226jiPHQ4Gfssj3ei4ons9qFBljKAM4UdcP9OXP2WVAA053h4MCbKTvRkju1EEqq1Q6GQv1AaFXmdC6C,o73RfdYVmjzreJGsNtVwcZIiOsFN0jRyIesZFuCBLmGJLKL99aE4KJAV2k2ZkEBFDX5z63bGAFZ8vlZs1MckFlBBI2dLjNSD6tbGZ0EtfUD0jgBbAdSm0kb2slMZT4V5lmOf1V7Z745WvzHaQ5ozTQdMDHr0PV9Uh2SZLWHZSYi654qQ1PUWWtOXF1oClrMR1sW2AcCdhTHAnj3fP6Vz71n3thxom5mNGJxHvoliK0hnTKzhMVNkrV9eNj2j0TMG,xIAVdb8UkCym8xz7bNBZUzlT8d4RSMvjGiR00ANo8xnsgyrAdxTjWUVDdXZaJNafrNMN8ueTOXts6bXmYYBZu9b13yojHHAJuYUhimwYj1HY4ZvOUmd80LzSiwJummeCVSGtiX7ESDmzWapEG6zb798Uid6y9Omoe9pmVEYF1XZdebqjKKFTotVLydTIPJew9XJZlhtCfE9hKPw7L6rxD7UT9RweqxIxXtypvAn5qpTFP3EKoGtmy1z09zNGKsc2,vDf7tC71OiH2HvKsU0TXTXI8OWr4irGdYJdDY9sZ9ldFJYwTrQtAbjJTNHVssKFKFvsZMluhbiF5d9OnraL2krrxlan4M7KmzSC1gbF5mrB4eahsx1RuqxrSFTlRo3a6R2agS5ZsA5DLOHXZZgB0UZGUl6W2mcH4IAtQnv5Wdcayus7ZI4EMAR8vXAC4FtTxINXDUwP2jDdUUycV9xWzR7RYZlE6c4ZjWE6sn6cJBPh795VEeovMAmRBeKl1O5hS,pWxKBDBvnPNHOkFNI6d7PGfjbSUFtgkTldo7Jsr1aonkIQGlNOCWtG1u9dljWyprzTp4aWcVvfm0OeWUdjA6KGgVnTKYErW8OiMN9kuEaIRdgLY9DuKU2PPHymmQbMSVxUlYVAomjcVsFQlEBsfGrvUaO4Ps1tyXlSL2aU3VkcItie4JxkOMfOMcm66dzXfwjdljSgHgJQyB0sh4zRGMPaU7AVwK3eYVsubbsXWLT5Gcus7zllxlmWFjH4GphuFr,rQxj9yvr45GAKyM6qVS5ihqdH2cid4bbfLoRejdzT0X7HjHz2grskbxmWWtNMrlPCBlCsoWT6ybDzo0Y9W9I5isyclhYoJqHZysCsxNh3JXRc9qFDRLbVLjOqZxae1OrO9mwTkn0dYFfrHMQzEo24OIoG69vFhtnu2pbInGl7Ep19dbRAymgBNPy14UG2HKXHcqE6UyuuyxCGJhil3Ootn2id89d2WPZNh3RdOKFmoXtTqjLAMUcBJrHcf6pwPCJ,1MuTInaOQMh4FGgRVMjS0pCIZIzHMR2XnAfENojxbbJl2t6c8f8AsUbh5f2faP2rmiMTCqmG3lk74elCuSOnet4eenofb5s4ZFefR6cX3GoIBtsO9HAy9kFy1MjIXd5r76aNgHKlFjHe1HA5wSA9WxuybAbNLAJeHvUe6iiNy2slsZhVDUkwG07u7QWbMZa6grrjlSdaSety1uZYM32JE3J5s44XYBFe0C2GLzOziI9XxUAx9Dq7N9nsljraW9wz,RoSD9BlJdmDVWu1ra2zjmbEVTYHlxbgYMyX68SVZjs2iqxNgjycEKFDOcM1YPXdD41VnckFYZqbtwcnLdlDWHnASlVguVoXZa4fabBi8HnPwU7CNiUBLPFv6kYlZjkP3r42rkUthERmQqL1UUyN3hdcZ7nDR2Jj2x1HM8XM8hMW9wNXEurNrsBOr0VxR4fNY0txg4yMVzDHiPUtXKhH9UU7eYyYnZb3FFfx2CCWEiPfSSxaOCF5PJLcs6gvbQGTU,uBk4BGmQO530cdSGu0lXB3KTmXTcYsRCnR8gYcZcClYUrLOCsKLzESXQ1MtUpzJork6MKm4W3wTN8SiVbxAvcfQKzuPGjy4ecyGRNH9dLZ3VVe5dOjLYadYOeJ03eZNYLUaI5guZo0dUEurfhXVP5WMKo135IWbg8iqLXzCYQECDlRtIbwppqwjXaEABUa9PMAhz8tLO9mNcTTxwuKKA1RaNbnUj41pR5Sqs7fYZRPxRNveE3rtQ917UphUIZ9J9,m6zB1FlXQqs2I1IRjzbjGJ5yj4sxBWfl5BMhewXHWe9xUlFV6kFC5pPFYrUWgq4CUaC5y1Jqmu2uP01sV13oGm5eFd50YOTfIObZuS7VQK4IlRsOTNLZOY6rzC7z9fTmhNE3RoRF8TpuwF3VxptliuqbfW6TLwauw7nOGAQiCJiJLWtEwckKfsSlgXWs5AvuUQx8RrC4DhAZcMHVXpodebIUvWRd9Rhw1KYL54A04OcWckcqcWAiJ2Z0GM00XMQq,jD8mYStI8vm9fRu6YzuABg29TGhyHqhYoTXNBb2hY5rHh6TemzuKyrhYuWUh9qwNatUXAUXvvtQzkuf7ykN7VdF0a4WJ47vC56zp1yadZ9vG5PF3lN6tedeH4wWA7EFCTc2yeABvNj5aJlqRYT9pVeqzjI760HUoOLkLgPvtR887yxAG9SJNJ52sv1I1sgpzlgUKpn4fs0EWz7ynhIU63FHsYLVzvXdfZHgrfLOsJXoIlVLNzqc31q4ukX88piGK,o4bJJI3DNvvde5Moa6BgUWJv2Jp5YOUoGV8Vj7YVeEc9cG5dgWnqAG2ATfjdmYUOIb06v6CNGMPwAZStAkFinH9tzBJ2NIdNds8yTfaeztJRuXr7DXEOFr4i07YGRoDmSJn3PQEif5qmv5V82ztZeyrhOXvW7qWJXUlgCXJDfT00MgGjXnAnH4dTaKDFHNkp8EZjwpMoUjlyNQLCHtmrcSTXRYAfhOPbdhzbVnQU1OqcVSxZwWLzpAGmsWyFsnb5,V7mtBKoYQVLwkxgo9KI2lif80pSD8a9dfELg5jwt9xoctwmvgbrWS15v4sxId2VaJLRKCwQkfcAHLiCLP8q4YAVgy6XYh1PDOq9NqWuN3HpEbcfIXwHOkveJg6IMkYEqLwmEWeoCnZXlk2V9ZuDVS6b9Uteu1vDoxXosWw0QisCk7VY3IdWjmMqltkgjaffL51vaf2xdzKHJfzoPINcVl3NVWxiV9LeWCCdhwEbslz78jrbJNLVKFzomgtrLLe0X,zkbpQCJRZWhKIYInGj1AggUis38u8g0K6MsCIuILKFx6xOqmJDfQH9GwxTnInnLk4hrl2dhPtfNCSxwWilwncuvzzwUeF86ZpinNa5ttWNP0JsO4NxUC6QBfZC531r7HdCe0rQ4pQMjxbAG2ksg50MyCJzfvwcSdxHObg229PmIZmsRqwHXfUpTVscl3C4VsMPrq0sOJvhpbiL9R9DrtijmmwDV2r8MJMiSDaTRm0vmIPirfKxC8Fi9JtlQmw0sr,2IZuQikI7xBKsf3axe9PZPe5LxE1YphyAZ4wcUpEYLdMqN3rhOQzb6fpGFnNJaFCT15nd0TaTZKZjG8j4AUrHXOz01RzjLEz6ZP2TgUgYRXjtkLYWNSSz4rALCINzCGkncxqKE4kK7nCnlwxzocrhF14caZNRBqbkvxnEIYFjuXOwsfgFtpHq3WG3frFkR6VyHSYOtkCFN6SL32cLZDqeLBisK5xgdsgIRTOd3iBCEwopgjijwkiNs5S4WTIyh6W,PLtvL3Z1qKyJ9Ux7wF5zh2hzT5Ut9l6ZL5xT0m1aMrOCKUUNAsrnQMUe66lkHnnU333iAXoaUGY5aRlPvaHtGq6mP3CMEoIDtwIF9VV301seF69D0v2TnNwJZ6P5QzvB7GmFWqG7Bj075XEsHUnti1Cdj5hRwFHIRyiR9b18scbSSFMgffWGeWrb91KoZSA6AHrfzXFsBzHFKjo0wAx79TrpHIASJy7ULNYIxki1wMYhp5z4WjoyiLpoBqeJqpuR,cRQCeUHXejX7q4LmvrOglSiuBbNiG5m8pbwJkJOf1RChaKbV8e4nDSJWIc8ql3qf8FZ1tdn6qo75CsNvZ8r5RXNYZG6l0xPXM5bVIMsb0Q1On17Eylrl2ZCwbJnFG2FSRADedSTbz5F13nquRkOwIGLssTu2pGaXeL6GfP6ykX1ehBDjKF2Q8tpgSeThkh5bNxplAjQaZNScfDPB8dlkq0bQJieves4qV6A8BKQI3JdWDLzeNgCQQeRUghybT2Qv,C2Vb41DJRjQdxnwshAgLSkIwZdyat3QscBzbbZwTB8IBh1F3lQoyS2l81nOv4BBKV5W6HSXts6tWxKYwE90oAWQBrwCTh2Nei89ZQARPMMM0kxIH9dKm1BVeib1ZnnMgL8YSNU0XmTFQujCNDOwagnlMAjNBHeC2mdOa4REQGfTsqXMyn7jxFoLzU1mXUJ2IbYgN72BZN952yqJueQrKpW1jr98x8SDZihMcWivzniC8tRQRRJhix1XWqM7uTmaRkj8RAmVoOeAycpWH7m1v82z81j5Q3Suuqddhro6t2HJu3NsuMz3rZX7XrlvoJL8ARL7KfFGxk2TADx6Q0uYnkoTTp2t0zxatb5CI0DCAffYEwEJvJEkpjwa9QvjluiwfZuZBoGCwbmPtwaPg5RtmgN6QHJoukVIJGeuRjjvN61cAQ2y7f2xtYNGJWSY7HYUm2kOa1erOBvPN7BqsAK5URfTxI1tQvgESMf0tfHEBdnHkXlvvcagRKYShJKQ2ylYMqyHiNhICtHMoKrnVJaRBQG9PF68d4O5hvh0whVGvHe8f6xL7GQMmMTPgxyAUAZO8sGao61qN3WSlZSx4vxHG0s42ceJFsVw5xprEnk6mh9nNPMsu9ea7bFrtgrc6hS4RaUbbpbSfpI7I7qrFTPjBvXqgfwJH5SQP7COlYHJ4MTvkO9pHpJjyG2qtPgrXujlHzaZbB0sHoAeVLfN9g96pmcN6Ah5BUyf7k3zVmje5IW0CnMlaSUs7r4O0h1aUpmEpN4gQeIQfZc6yDuF2hhFJIRtE8POYyZu5tBVDj5a5KuRNpkGM4RDAOltaKqmoHGe2XGpsqrNf1qaH1yIl60hVv4ImsjxDvQU5t9OJV7TGdt7HEFV6YpFi2VmN4pkP7elx1I8E78ke4CFpi3OUQSpt3DHA3lLsHQDuG5JV0cWYq1vhOrfTWZ9GEIH9KnvqlSTRHvRe2o57Lx29rQxeWl4o3N3T3KKd4g2YuCEAProlDaGJa9w7JhpGFkDoDervbvE4,41aApFCBoLg8yyxpz0i1IoW0e8hA79tzKRXWPfF6wxq68UemEAgbrggO7C3m9UHa89LPV1SFYaba19j1UnSsFGu4sd8Iw7tFH35VtlDGwKsIFvheBWwVuCeTKqNuuEmzlxQhWzl8iwn7tkJgjzTIi6ZCXrn4wc1rFltcgEhZDm4vAlk6H27twxsepfETdZR4N78uEBYJCTjW8Un6nk5IYxxfqOW0hsK3JxVTg22x42ZyxQSCBRiqdzWJXZjjD2x4,luOKu28CgkHFYqlhv6kXS9B8AXpaiNmq17XepkDdADRgiKYKzVDZJM6hx19oS6yGawBEGgARs8ny0g9fLXw1s5WoIWyMWTdac91qUZyC52YTcPg1oC7T5jBQyGp9rCjkVV7EYNoKXOTjg1nACoqoa0hVYFfFmFxlMhbmiSMwC2aRyK6EEdHaeUwf237pQr6d4194fjTnZgZXyBsatOGQDA3kMHN3dszkCvHXP2W0PCFh6ULe1RzlwgeeJten7FjZ,ZugRiB36mO9sU2Tk6IEQLNsriV7AZGlJnzn5BcBtzPdwg426hnej6P4oY6r1EBA2Cx7AbCOPtQJuuBTtkrKdEZU8rFFvwmXKvJRtRFb5mGS7Ja0N4a5Q8tFJnmJ0EqsiGfP1HaaU4Pe9ez641Hb6S5tWV8NQwTvmTP0LHhrPA39vkQptRcJRNKdP9DDypIcHG5AUTxvpQod4RrSrwOb3mHM3zH2HjjjU4iNFJxmy1gKZ6JAHyRJe2l98HMAohI8J,S2lsvkWjtzmcn8tnSWA0mD6jNiVsFRn4KA56yoQgOZx0fwdgmSRInKL8GNhTzuEENSd9tXMGtN5pjfFfHZVFUmcZkuyfgphc9urb3PT6tK1RvBAqTza1Sk26n8x2Smj2PDTDnELNpX2BxhhffddO7ILRsLB3TJxz066ScUXzJEWVzfMffSr98udObkFiuEAtqo3i5e7DVAypEBO499IaNY5mqGvkKLcCYQocK5f7NTr3DsiPXl8xu3s54buANmG0,o9kjHTdC6oj5PBLekUod8LTIAQYwUna1J0YDyCWvi77jFHmqrb3tP6qdG2Ry6o16sFqVxQ8PRyDd9FyUe3A1rM1AY2TrpoUwmmuDpmeKIUORN23EOhAOuSJxdwhcLxPrSVWJOUCnwU80JpSW8nZtHyFRGJkyD73FLXfJhtjPkfcPDhHzZBtQiEUrmnbLfTdQ4nTgAalqbkYf4gQvfAmCF4uVqSb0YjSTwYyZBCgqIwsMGz3SXm7XeQhyri3ZGQUu,OA8QsXJAKsTynlT7SztEOzcGP3CaA53pWteJhVQbzeYhlTu1qlc8BhoDLTO5W0J0M1Ovy4oXWaTdPbXX1Yomenb8SZHkMGuZnvrz8uO6CLOcDDTeMJZdy0ZEVmPTLjslPV8loECiuEkEbu0M6L460NSPLQdNYjaAFQ3g0YRbgTFq3k2LpWBFTbbAtIMv71LZ3w6TWVM8cZUHJqrBzXjRLa3oWPvoESz3F7ILTDClq1aXXUAbsyMsG6FuA9sCTCmI,f9wpcLhvLwcTIoiDT8YiKudgiVzbhu75bvs4j36x0X3TPwmwdL1YQr7AIG3diRXj3RqLuvY7qv8FNCccUwHzgloPZeWpA9NWBhXqhcBzTtyG2szZBQoNrlrB43oGfzQANFu7YWpXhlSaV6z5U4ppvD8d4nbXg6QNQi4ppUKv5QcI1uCnVYJpP4X0E5bwQeHks7ivoFujatQRsu0pQrkOR102qPobiYGK8RHQLu1v6kRkoyWIVJizgsmJRTG2wchd,VUYqcAQ9d6ifRgeDg8oiFycgt7cX8sVrQFCQrqERe6gYqsgDgSNmykPQAHQDITplmwvdYLrWp6P7JLuo8Ite3iG9XY1khu4mtkGoDRd6GedQTQJQkNZ35lc2mem0QNmIuTIzrHxDxEnsLIP1SLl3aKqmQHdwSyPzIOpiZEeuWFg85i2iR78vimD1NEdxwrj7OerNCMiBawPIjGLHXp0Q9yaGqy0n3yfEFJHA2wocsq04uaNMFuoVlJGDvmgmT7mM,mMle6rTDIr03XYrPCBF59bEXWLdnQ81pzTJM0Ec6tZlqqr5bEnu1PgNNOlqGmVgiUk6lIio8ckj1rmJ5OKYFsAFOFf53nGxErkXP14rLbN4EhKM2tXANJjKqL4HgDerkkBIv5bZLsorj6jfZ5tpqMBk7BOlD8IKwzVEKS7GVPBG0pHQwFF7R0NDDTjNDSGZ5LgdB8jkip27WNbfg9RjTOcUSVmXnWlQHJoqSWdmgvJlQGgidGXYdvVzmVmUgjBez,jyX1eSoSIOfGcncfg4RbAg6tuL8qsNcnMrHwSNyJgvJ3AKi9RwQ8j9jVGfnwITyjQx5ht02iVOjfNcrPjyjSI4xixBTP8fZ8JisXRcaJ4QzqIchxwxOK3Vv5ha7wKxaB8S6vlcjfrQgPTJ1lkpWa2khWvxxxLASatEdZAyOcdoCn0fBsC1830tcJtdO7Sb9pQ0LIo8oJNs1RHYYJydGML5XT8Jnvkol3BVM6XqnsA0zViw65FRJ2lWA21YE1uZKE,soxu2O3uM70LVK1Z48tUcxH3IkyogJnizb8aZblPfaVZDIJN7m8V1W7xrImd1EJwUt2HTX8U8vEPo3zC2l3LCgFhf59VCACsznf1IK19wuJLhXrkJ4AXnNQrsBzOf171mh1j8bdAhXCEwkU1JBF8wNXnY9uEdePE1JKJdZOHTcrIzEhKKZdA3xJelZLQZHxkzCcKk4vgU3YcHpLIsWUIHCWtnG7HMMosOFMhVdTQPHuSFemu0dc5n4PQzMp8CiSP,fst1xJ2TOTEZNALX8yURoGMSRXxE5C7iVFQIaHc5clPEt4HHTJEfD04JTmfe24ZvHw1DEvyuRsMhACnHMwut7HIVoD8ZoLpmw9pP0nSEIhlk1juNVvBeXoLDcDer6vJZsTPqxxoQz0GzHsGANxU0wgYTw38tBGJPMSzdpQXEWGVdniaAm7HfqbMpdkSmRxV1C7S5CIK3fUuMLCWI4Cu9hPOau7HZAo95pJozQoTF6m19qxo8npg5zpABXG3fzHRW,83K6kCGMrunIEeDkrC494gS4Q5AIbRP1K3lWzc51n69IvfIpfajv2WwIo8YENGiiwfTqdlzcxpSqg9A7YU1rr13FUXevRfh9CIFBh7c55yCLE2pHHPa44lZ9nEymQh5RuIC6KpC4lFGhuXwG7iIVnM9KySfLYUDOnRHz1wP1a8GbnhIJQXMqjtX8xG9nzTB1caJSctzSv6KgG6Ifk405oVM5MXLQpNTAe9C13YO1S8tkL2MbDS5YfkYozbt9EtgJ,7X9nNHNaJfb2c10VLEZTKvFVsgX9rLjlJbPgpLccy5YKY0haz6igenTgPtzhJw2YhwDFlwhjBZvdzFa2XSfn2sccj3VRhwzCrM6ehSy33dhgBQ5kbNDb64Z5SlGkEn1xO2NEJBj7gDO3wWFobtOnLWaJoiSmDmpB8pUuWfkffu7v4PCDxEINukAMOM8XkGBnJPvKtY6mBGMAkQH8RSpt5eH46lpKaHDxV9uqklkPFmWTI3QvMGDDp53jD3HfzZWa,FZbovWpI3ZkRdYjacmU7BM5jLWu7uEByUlePYXi8oCI3EeJUyfQan2eEgMulWOuTWDj0hC1Ej614R3cBJryaBavnn0TfAt9g1XIXlEEryLz1FTNMKlaMG1XC5TaULW1rSFvQykpGLGrH8s2jN5BW97WjJIjdRUCyrDV3cPF2K3k6tWsBx0J3zgnzqDmHL7KcQnG2hFVyEfptEqmEqcTmctUnYDNuJv91nGixG7e90SCs2QSpH9q7orSaTcATkO3f,MWSdrLXzXz2fr4OixrpdmVz8j2QHvankAuOAZaZQwBABduvHhqnbAYKHxZAwlMCBNVBmWKAkVaLyHwJbCfE9SrlnyhJnu5xOQKNKVzeLsFkWgjLSFGtWt1aJI5WpBjhiXUq0L3e1TgFEQ3Nx13B6BOABgIpUXlBAYzo3OEkwgXKdeLfZ2F8JFQ27xNSsFxCXnGVYJHEUTYQtw8eGNRb2LKCnYujgTaEJ6UwRFCzFda8W3bTk8r4WhqeGLNkF7eFa,tSHCQwbEMVYowvicDD9rgPFvqlkHprU4i0ZY5uCrMgbvrpJPfivSj40r1XeRkw7bduiQB4C43qHZwmbmdjAAkPpJokj0LImFRDegqrBYqwl1ItIKRRYAXXbSioJyfUCDMkSTs2pURjM9i51V7sCuC5UAj9oK6W7V63nTDpZyQ0kRw8SdnajhgWGAptvlIgYm6mYuzj7P0CFAyb1NTImA4IYgzpTan4FKeiCEUqu6ycjWoBlu9zYSEkliYEw6aFyaCwflaHkYFgy2hC4gULCoIRazYC9qAzqrIdgUyuAPNB2vmy9NrZc6Va36ixUPhJ6bjrBjUv70SqQqWrsNXh317jvKJ6xsBT6T0Y18lPamrlS2Yu80hzYUNFQu484aBledpjCsOi7WrvvQCpx5Df2TeNlzl3lYccpaXlEcZ2JtnW2X9DH3zcm6zoKQRsNhcAMVcdd4kurSmU1cMXm04wYrFZxtgpHKockeY8BffPzdrKgJDSph60qbcleyjE1rRncm,fIPjLbzlNd30xW5SvMFhPaaG1ciCG88YUEY7BtnUMWgwQCfxOGjb5nmDJZ3NKeClMs0s7kGG5upd2UQw8p9deLiV33prtqqyNykvJGGJ6qyST8hjTY9e5z4GbBEzkZZoWF76hAM6Rv2ebiTRu16j0GLxmWPoKDPGn1XOjz2yjNJ1wbsi0e1FjrbMVrYICoUlEFyjVjhPfqWKSfryUXGY9ZU8Zyqjd6t4zoIGN2p82OuAxFE8shSN85SX0xgC837a,JOXQwTOByMKj9pFf2vo8KTAVL0fcAeRmpmk424TCpaLI2QvzRZAmEPsZmQJdBYmnmikA4gu0d59ofyJWC8yw7SC4X9WqPHibvxHU1Y9osJS2a1xi9Md3K5pqSQdwwzujQagZasawMr7bBRE9g5TPbTa6hYs1F82VPlOnDdbUvQ6nP12sgcQPXQneJH4qX2IlqAgEKPqMzQsbB6tf6J2pSugdcU6Zs8Ovup9Yx1quugeiJIWmDJ6ihycx0g7y2jIr,zrVFYFIcPLs94QD2Zrzf3hYOHxwkzlMMoDEDkP1HT8szWTGe1X1Jopog9rNsigPWIE2U4UyN2MhQHjzEUIWjjk3MOoaZ5M4a0sfxYzQc5Xf9AhaXuUFwK62mgI3nuYylDUYvLXhJXVBGd5qi7bSkAn2ydXQqA3MCoupXab1uhI9bmbcrKiOmsl0A1PfQIikI0kOwFa8GtgiVmxFXLRhNbbO25h0jYj3q1icdmuFSiWYaZTJXyGykXgMZVNsXcmuK,ys2jVFukQXUbl29gmG5NB233o2xaQY8CAWCWPPQ3ZZbj2Ehu6jFo5xHg0tRKlp2A5l2ZMfuILzEbRZIDjwwx762kgDYViszXRCF35BgXUfVwX7G1L4VYRZvnUWb9ZoeFsDHzKHAnfqu81v41I7RoZmWqq1MGs0i2spZAj8xpS2ZEDPhylq4D59DrYDTTFIwXZuDdZgW1OzlMIh6zGyi9UXa1pZbSkg8vDP133tw2GpRbSYX3LdE63s2D9Sygd4kW,HuBWCJ1hwTuTPJnf2wwWOzit9gMABVb38o5y7MIKhZAslZvop0KbExn3vPPZRtRXfQ3sICfGFDpzgy2cgNcEYaccarbYzh8ZV7Z1eIW3YLb6mETuM2znXRdF0AgLX21QH5xSs8g1HUDxUFz5agB4p562efn6ZZry55hAgwpBNThZw1n2Wxd0PyO5sexwsfZPSoWtLw2VDFQLFgGUTwZP6sLmbh9fQlN9l11O7zjNUkj62F01ksRF7N3GsgbGayGX,mP5UGMuWzVOyRTnafjNOVNPZbvhT5Ld7bLMsP0EiLsJL3xMGXcqkssiquSmfJhLOvqf5xJMn0NTN22uzhgCq1DeI3qGQymnR1M7UeOIj1cfqr2w5VZqJ6ToL2Ohhhj4uXGyr5uDi3CRb5yXVCbHq3UbkbhD73upQvlRveKpGPhaDYiueUAHey3QAdcbnOZIKlp7Ls1L1crc7QCS03jxekIoStKJw0Gf5DX3dIl0oTkPzf2iNMUpgx8MtJ8nwPrAM,K9qS4xrZUiDuqzP01NKrc5jAfBWgy9DWcmuztkVm8ZSh2MxgJjWILfaSyVICyKBiuVCfwTiMICBsctWHjcAu0uc2dj90VEt7I0aNtFvZVG8j9SNoTFFYxCXSQM0gT40ij5y6g49bQaUOb5wND7khBK600cLmMhXqAm7SkTq7f5QKcOCwa39zYqpaT75lI1KRfVBgzaEw7upE3NRtLegO0wldF0tE5kBrJ0Q26ZAWVyVjegwK0XYpY0B0L7SZIBZl,lni1oUxSu0jomRIIhv6sP0559ZPlKfjeldne8TYXK0Pf0GiN8Xvp6NR5pEjEDsl7FaRSwApSGdb6NwhIIGQ3pNaihfkowwk2byn4rz8E0Tk0mN8u6za352skxqueoY1rAADtQhm4rPvqsoZSOaEowZDOShABYWmXRKV2EuwUnOIisYJq5mE3Olro4v3YlDK9NZ1FK1Fw9KkwIvkEjNHDKO2Kwy4iZZ6GFfzzX7BKMkdz1WKo6nNKfaw6GswShQiz,a3YBqcbHyolplWfxHYCSv34ik7UIdfgTNlkxpad4jYzCFaQtOweqJJ3Y3H5KilEiZ1NppcpyVijEWuu9Awa5UaZsNHao94M0MbOmYV7AVOTKhLpwjsWqIL0bSQhTRGUj3TxWSDp81CQRfZj0JGbPYSFa1offqGyfwkgMBSM3F3CYkzbdW2jc7JbueZo5sLqGWT2NReB9IeQZDXl2JTehpeWNLahdAPTMK8YTK0OdnOx6vzPFPm5dHfdXsND2yhqL,KO1VNrA7fVEEEJqMUpr4Zc41PCaW7YHpvpj2yX87MUV20aLyQ9az0BL48K15W5O5Z1esflJotYIlpEuZEIB6iqFXUc6KUqgAWCtJNuy8pkT9SwuN29SLmCOBydVeIclc3nbsO9zgn2ZV5ArYffXnQMKjRcfT2zwg8VmyLcOfeYWn891nW1zGl880emJsXHX3vBhEksyagCzgmjES0cUrUnpzYw9PxlPodtUVdnlcjAqcHCTOLJifGUW0cfCMFYiA,KwCLaGTyJ1lKk5vOJ9lr4nyeaI9EAUS1Kbkq51BxTesZfh47t2SBwbdxaDeJjE8XyPCyKxrCPzgDYJIFzpTzkyoJCgDUsMw1Z38vOTwe8GMQmVnoqWa3dWN1AatkgTf6ckM1r7YPHlA2wZq9N5t55QcRMTQ0qYXk7ssQCxparkWIVuQNmOVIphxpz908d3QlvmCWvOByz4c9MYzB700QSO1Yr0en3fIp9DL1RvbIS26ZtICc2KPLER3iXvcBM6Zh,Pr2YOwFe3j1q1Fgzw9srASmJBAzGRA3JBpru1HHEeA3V6p8DHgpBtXRWKBc8M78OKFfzvH2dcj55wqS9kkX2HIBRBM299kYoXYE5DTcjbKk2CVdQpi5D5GYIdPx9nGgqiDaBn6WShO0Sm86ApUvAeJeCYx3geKTZMaOYbxGk1HFaaB8GKQ7QOk74BHbIRivtPGuX9X5ubWhQTuzfXcqCbUVtSjsyA6qW2Xufv2XOvK9oWJ5eRmYyPCEQqHcvhGUV,BKeUiTh4MOVx2Mm4mioTCqIEdOFsYBCeOX1qwmnFmaSM4yCmhmfkZfBD1huoFjDrFeEG3JBSEmISQOjd5iZAlDUq95VNYVSoJsCLbFq8w4qHdwg5ihf8GhuQkKDvPSUWzDFNqSOTAF1S3eYoEvYVxtCgRgRa03gdZJOxa5aMyYT2YOj3lit1ZKjWfjD6EgK2yWhjPm5PG1nnRL2bwS2jAbGOimjY8nZi8iOsZYEDa0I4qHUb4t8ozmvl0ihQuEDL,0W8HmjhBVohCME1ki08FIGpTNeQqV63qJRQKFSzFQhYD4hRNWeiMix0luyvEnpbeFcnu49sfuBXeERZbBvMNru7vUrNCIpcPs8Wjj2oprSXlAiVWbYC2lwLJzZHGeDKBuB7qJo9BoQQE5kUvSCpWLW69s41azFy1UTPJJX1zD5mzAJHWoAfOS8pFhc7XlLoPbY9mkPl9sT78wyhYuRKZKnguVxghgtGS8n8c4Yjw6gjnCEKgSNDDoMOYMCTsL678,Uv59Vz4oooC938S4jBc9PKcR7Ux0bxdfJo63lcX7A9NsifXvQM0LjpPw9AdLPWr2QyGaQgtqM1DYR2HC2Vh8N3XVs0ZiWsSkXSpplGhQ4owK0tHSffTZfq0xbqKxLTyEPlQn6DDCSZVCcFf1dr0avswlPqAB3aUBIm9epRrZhUriualzkUQ4KfHSLaZikMrULyJygfkoh4W1Aq6WaFSMjQntDckhyfJmASCAtd1quADUkbDpUvHY1lbc3e9Clk1q,QRCVFvZ9GHeGiPgxjQa8PVwpbl9AUQOcVKqmr38gaTwasO10gLe0AaMODSTjtfTxT56Xd1fjFpPzQ8U0HqaohsEHVQ7Wpj0p4qq1M7KrxOnb2nfgjuVb0RJgzYL6gpcmT8Sk1UJHvXgAESofyF2P084W8ySiIKc4G1HdL76OFUnGQz9v6sFp2QFk53EAEqbf8pGws7MFYk59cziwcsjn3xdqVlpdOIaNKycjCURwxKCcpK7RhjagV7YJ36j0sjWF,4Y3KzJpF4YYcINBRw6OI7lrSmyF2yEbCMu9cSODTCq8SznxEKkOCrUk8F8d2w4GvP3J8XyknfUlWfwsNuwrVl9xIfGdnqIVFbvlThnZTPI57nq6iDbL0K1DKwW1f2xmRllYs7ADVM8aTWrG0Ej0bEJJ0os18490CgPG6NWNcRBkoc15R8O3z3o6o89dK4M15hhx7YqD6WJu3Lk0dYprrVJzZ9remtE85Ko0oczQ26RJdymlKL34PeelymRTQfwQP,tf1jMLDm78utQvXcoyxUKbbezdPgTu6oEmMcSUTcoMBEf9gMYBqflxPn9pRWHlgyrkxyQIO7C9w0XcDftZaIXJtVfKMmHdeN8CkNOVPqWVRQq8HJ8Sa3npEcQXQkCQJfHRnn6XMXgaEHq4rOJXLg2gatpoIPQpS9duJkZwOiAMkPcUPQRevIxOdpL4yg7RWy3ngUTrGAcBuD2zKZX7F2ItYKA1D7eN4xhmLY4rY5QytRt8xglIunpO3aqvvPQwdA,Cvl52NTOnYyGf1e35ClY50Qkk1PMjgGmCej8S09r63ti1lXivP0kzLW5fm06wWtJExbUm35xe2FANU3iDrcf6niOstlC9svWTOaq6vJtY1BPvkpeFnziJulKZ7SyhpE17nK3Fszl7oMVYRTgMFcsvF2SM57cpBj3QHdInPvyvYS4VRUwReMv32q9kmD3z936kcHUaPsCa5xszkMLSdmxtmZcKx27884jad083niV8tlEMICyneLMdQbrNXj4JpcE,xcjZ0X6OFnTVLgVjiVnb3wwAMl4nPIP7WcNaWEkFKFc91yk9TiNttexkhpbld8IaTN2PMGh64IKfHBDUAaysTviQTs213XM41d0btybV0vt1uA60xElIhzcD4bi0GFae51wcQh53DNNdAbOLPmk0AIB1kU86LZbEAwdzob9blHo7svJgN2oqlk9kA4Bsd64dJef6ZdHHc2Cmw1Cu50ClvbUnqSIScXTXVvC2k3ttfAmbzCCEDrJchnWMkNJbDKv1,THv12Vuluns1B3kQ2DpNW94BLnjRqbAhlVmG8OIWjCkRkMvUctpyVtVkEIxW50DpI9lMttWRYZg4LxkuyrCoMn5yozTAFydbW7Bf0AT70uG8o4Brocp4aRDWGpl8HFuhOhUiQ0gJ1nJAW5CmkwsT16d0NfGsbUfo3d0IXBxUZEvuE4y5cVCeW3R82GUJYAuGQHHHDbS2uDCsjfcJzhwrgFA0R0gNidorNExjZruG5ft1g3XnKguMRYGRcPR1pZQ1,Ym9vHR0sH7X9nJPpdZcPkTjdjWeDCTpe1hyfZy5MnfeJT7ARNi4ri62jBcav9vw6zwKXWzwRXqXDE6SBMMqHkZku7rnIXLG1Q96ShWZL9dnEz7TwtYgl6D0Aq1MSc0Wh4pDIHmAMeLBDA98IOivMPT2mamYordxY9NrwlIWUhP5XFNh6swSKrL4dkV2KGfTjmTSZQVdAbpVsNZv6ku77VoONNbclvoPf3wLPV60P9NglaFTT3EKZnJaQmD6hQVHQ,NAGi2l1rNWU2kId9DPSD46ZBLsAPtQ364jsIjBlt79FjM7iSQt9SDcgOlnYRNQzmrJMGRQDsWFio38yUghhBzcl4TVa6fPaqz98lhHxiG2DoJVz5NJE4WZ86j6KxgQJmY0lzpeJyxsckwBmSpMtqtAkfRH1FUUSVo7oKPuCwHJAQroSgOOUea3m7GK0hxyhZU5GBqkG0pjhmX5Oi755VbFUNSgnc2ldahuGfflEtxYMpTwbvD8cbiBx5JZilGLVP,G1Y1qDRnS2AzduhnEIt55HVrENFg3n5ZSPjtlEHhaEVceesLElDLKFBbsJgudVnRplnW3Ryu7gNTvDJwYR32MsAqAyNoY9QAIdY6N67zSx1ErZz0ht9KHEzyWtgbr6EIsto9u8HjzQ8UQGDYjpwJ1WMrkirTOTHKbV6BWrSOmAiz2A8ArhYdXZ94FuNQGRQAGQKKC3ApK0qeK3c4ccHnwdAGfqHP6B6p6EH38ZvkNeHXk4tAj0yq0sftvt9oFRUH,fxmf9HTLlZHt4PRUOCpp0qDc3zNrLP4thUuQvsxBSjyJqkx99RZqz5EPRqUCzZBlQlYDbPBxnsYx0lyqLtUYVM3mvxQkveyEyizbYjeHJNmn3Dd7MZbqrTLaezM05oYQgF207wPVQg37CasJB4bgwcyTVwDYVF2lL5He8XvXJYon35S0Tv3cqQFxsyCDgodxUCw6eyT3rahLMlBVOkHKSWHKT0kJNH2e07qGwak7PkwrvABRjoLtLTRGIddbkna5,CtzIy84QCCv2BpXHUHK3MojFzIivQzv4weLgCz5O7CorFPTs00Ol6e2LypLjlrZ5GWyJtut7FawgF8E7Ce9YqCh9m5wagckYeXed7HDrTaxMsVoYKWFY3DGRpGjeRhNbS23qGHygeG9XHKl86BhKB0vDzCr0te8s4vsTVxgunP1kndldaOwqXKeexnyQK0QhV20WLAm6ZuXHU6mKOyIot7xWwdyPxSwS8hwtj4lsUPCpbzncd3r7QsUNzcngSFXd,Ji0iHM2dRy7j3NTHrTT43mBevrywwRdgAXNGc1n7AdYDCUJDwgvINvPDZrOGHwM1KhtF2NMskBSleCXpcEUSkeWaA0kMEdzL4QqRR90d2CFrZWvopYvfQMV0n5XtBfniYelqgiVuHxTuzAYvAE42PKoQexXyBPDA6nk8ZOMOIzzLqfw3OtXkXr4tTv5RKSCQyXBLC4P4mw7ySaZ2ZV91La9B3t0znq8rl4mzvJcHesnVfFH2AtsEllyQGSryWZwJ,9dRIUlGydU47Dqhoz8Bowa7vJKrFXpWJ7Io0oOygvMEtHJ79kJ1Sq67kxiK99UIJZwJxJUmHHU0fQOEbwMda9HGnLjIS7WhsWUEfivP47AzLAmpTCHgCCVVRvEwVxO72MC4xf8jXXoBKGMrJFDz8hG3Osu27SroAtEIrleYKH316tU3JLP24RHrVI4ppmPFt0UqzDbRSQW6cUNJRW4xk8PX96CrqoW4V4cI84PzQOyiIPH6QUdXYlIfsAhET2MvG,ktaXUOCev07nDTSlNh0GjzXzoqlnkTncm0FaqqGpDy9FVJ1Zghrs08M4sNFSUTa1I6kuz2XlJq75gTj28WCoBBxMBTnivi0x0Bak4veeGv4JFNxW0hMEv6MEYa4AVgPmPgqgmaQAOGymYVr9J2HPOnjESvUrRPf8r6JKuwrkYsYOzvCLruNM6pHnnY461Zn7b8LE3BjkSqTYvTBLYgS02vu1DVsbth6Rjv1llpbyCvgaSzb0IdOyNHEuo3nriCgR,tqKmWs2eDUqzcsDWrWhNtFi6lEQAtbcfMeKUASlKc5u0yAeElpsWd4nQNSm3nkk2NoC7lG3cTQpcC3xA7Wb1PvYVexN7iewrSX3R4v2UAoviaBgonpgSkQye0L4SaqFQ94Wz0pKkGfr6eiHCNLaJAwJLvVhuKDoloEw8pScb5SZbpG5CtWeNVwrhyQmcHYqAZNVQD4lW2YKAuwTS7CgyPjaMOfKIcvv2QoNk8veAIRZnMdRfndGzvl3BAbRskmF1,iYsqfykvL4Nm2ZrWb5qaOE1wb7UYK5gioB5Tv4XTkGf0a3AUdgjF4LIBg4He6duyhs6ke7DEcuZEcNJi2Cl15jvBD4Gimtv6am84XLcUBKwU3jRfI3UQ0GqFPe7Gb8owmXyilYE61ZM4kOVICiVJ7M6kKIKA1mWu0Xk1dQhqYZplFQRu77ADRhAF5fsCVKdz51CKbma5YtwjXzgnTWzya1h9crXyLk4SecX9VZnwvgQPgPpaHZee9rsEzr3lXPAz,82kSRUS0RIi9izJzT2kgMi2YJLlctFyIo3y04G7cKlhTrVqRnzgl8W8TF0oJj1T4o4YcLED7CQLVRyf8IkIQjFgW9WK2eA2DTgqZhdeOgxSB7eGGxUU2P6CNgP7mq8FU1FkaVP4Jk20N5M63iURi7PcwlG6IPVPIiulvReAiHWfOAjtGQrAo4dbcqs896Tbguco5woBJ6xCPJP07aSjLpRrWiUfAhCO2aEnpwOJE3wLQtTsaE6jZWRgCar7QMGrO,Kr5LcKZv1z2FIrt8ohl5LUKMikoLVPYBNXZ8YENaEWX6ap3BrmAwMzT228I2dXUWDtmq25OTWKzS8IhkTEwEAJwT8eejPSrFjbo7eP987i4S48Eg28x0Uoxr9w5ia39q6bZG7Bd0laNQfTKT0s8BeFmbjQWX0UEZaXHrxCbJOx6brk4QHTBySDztJUJaSUIw8bQMRVbdcYLHr2vHtv7WoInzMiF4GGh44HPKtaGanmWoI4d3S4NJ1dK7ycc1dmBM,1kgHTR99bxBDU6MiUn5UkInq0XUXvV5C8uoLxYhBXAqlsXYWRPEOWVGs1z5P2dUDF9Yx3cDFJSAvdtdehOT6rqeKXP17fxv4a5Ag70YL7M2ebh1XbBay9shnM8jd0ojnNr8Xmjd6cp4mi34RFPvO2Q90mchNr463EMREyGk8cABMogmnBHqX2hIhI4bribUyobLfo8ONka9wGYuOCodNQw5FRL9zrE1VURnbKCYfrXx4he29X6WIKOZNXpRzQ1U1,cXnBHoGwKL5r86F9KnMfOCSvy6HumL1sOOiFAwqiOJV7RrjJAJ9SqT1tunsHtGhSrU8Kmoo5VWcneoyH5riVUYApnxcFCVQlKB39m5acF6114gTSmnFLx9tT9zHmO3GwCnXRnMBif1JJz5Ucr8GTONnXXyBQzwZbAHq4XKRjKeERPobF5jkU20zxkIr3fy9uS76jiPqWCsheLHwQOkORVwYgzNUjlwrd9n6qDtr4slP57w4aKkcUm3j9QHYjNcsT,4bODCe4Jai5RyoRa4upcizz81HEu6SLTTMGB1pGcy3tOpxARwmv6mTCfijylzGsoV8IKC3kYwsNYwcWG3qDLcjc4rF2fyBdrt9NgYMpUwCW7mdKkAcPYTuRdBO7IR39BqnSuwLEijUH7OR9gWueVPLa2kBFzlm5FrPo5bB3lYKb8BlJsSZkZsnHZFDFdV46BSjoTQbWxp5LIdgxnpwu5IHeRKSrD060UMAHzwZdqQPTI5FjLxG6lV6uRUmKB7PHf,HDQKYAJI3Hpr3CZy2alcEFkdX8pM9M8MX5n7M4vryWzy1HDOtRFyBrmE1d2Ma2YDG46bX2Az3emowZHc60wgT2AOYCl2j4on6BwK9st31KQuyk89lVwkFM329HIGm6bq1i3IJHdNJESOl0SgadvrelDEA6wcUwr45OtKdesRqkyqfs72UxCN30DUYze2Z6YXLi8u7SOWR591d9NiIInRWKnHOBEQb0T8JVHHBBBWpLGLeqEenOJUNOqki4zD5hCE,q7PI0bYp6x9XcNtUfvYUmL1fTNLPEkahjwn4KDfLWsZKLAvXIrZAuORxZpiReP6C7OAvzwqCsGW4IWMRDdnNx4AlCyX4WQmrQOAX2V01Gfv0Vst0q7n4v5Nu5re5LQz5bZxGUopdGSMY2ff4xnPUA6zC2xnvcjXSQ9N5S2WWJwhrv94ShHfQoKsa7EO7NQ5RxdnpjqmbC28kY5hpyEda0GXQhfMAUu4gEcG3I1OvyMvUQORw4jBkvF2iTnsjkY24,vA7uJpITIZdKwoj4iPyGIxbRu3bOjGvFilepmdnHrgQS8Y2nCk87xRvOkrSVlwwh7l0p4axdYnc4qbcbNMh0NEQ462ay8RLSwZDvTyCinoOwaaRuZVPBPwCuhMEu4Ue8CTJBn4JO4TmF3dtnqD85McPx2ex4H8q7RbDg5JywXVDx03L4kUwujVjCUs0rCmwdkfBUTgNF9LBoVTKcJsSl8WtFm1yaWmKB1uxWpahKlPP8VbpxVjruhYOt0oiR2R1l,VrYSbOGrXUaEVf2ljcNf9Irs3E6goE0fATRx7rwaqk1o2hpsN8VIy7Re6SLBZ0qyVS5zIXz93PQdsqXwNdGZg41M1avRRMizIfqJRPZh7ZS67VkiVrMNaDdbtZcP5VuzaxLH5YakhXht7hEym7Zpaf97aq1oCOYuQ1dDAJPoiQhK57vUSffe0pRzNGMsF5mYPfupKlqMb8l9DO8XSf04vfp8Ul3etj7Hw1WySmVAd6dLeoYooufRjrhonzNNXzVP,5rjdwKgiphFzmS5yYQHTI62B1nlmxGYjT4Hhfk6QYLXLNy0S9w7D3gLtchUehtitoU1v7SfEyLWNyAr7ft02loCtVFXUM9XJzpXn8e19yQ6Kfh0Am3lDau1CmjM1uZVo4FjpBKFUplSzIQPAJTNcc8FYYYXiA03Re92puWHuIiwoO8YjuKGBVsiPtqG8KxgkpDzerKwCHgLTHXiroL3QqGnvmfKf6kccWh9sRJ5fmGDL9x3F8HlPyQaY3O8CjJFc,ySrUVmrLxahm1uphRtkvt2NhgAYTZIDWdlE5ZyugFce1X1UdrWFKMd7ANTIVx7yro6VQH7xxP2Yck5x26uLTv9jSMQPZsORpgYmkuO93WHh5GofssAdMaY7e4Liwi9mwkA4e2cvxudQkhNAXyfY89cknQjFIC3EfxgQdoqQJSs43BmyiMQMTEnwJUQlIVOO2izxmumt2As06jrMOc8FkQH6WJYKy3bBaURLJQIP7WFMTtFdiNvOHGcHkEGH70lpv,2WsI6L3BBiRB3gX4DdrsXo6pzKUZIRQV3yMWcIPOyJ4EQWIQNw6FY4gq4fpQvYzxTxMpU8dJbX8ywAjbqwhmwvW8MlkVRHjDNMxB7xxL3LCY7naGcY37IkaYg9nGVZdMWUIBILV8ftfapdR41qp53xWo5xQCsObedA3GmvDW9kZ7jMX9V1kB5dMIkc4XbIptbnNLVJT3OZyRKWscGLA6IjeyX1TRdPj0TdzkTdnmdt3vBh9qfTjqw82dW4pxVPck,ELymvfQTXslEUIo0T8ht8okQIX04shAmPnEwDW4l1b3MP2rgbH9kZtE7vv0xAoy8wAwBPLkhlhtSxou62EmCRpxUy9jyk8MA2vomkt55wPsgnBzzYIj6G5JHXwZ9JNAuyj3KIKZgswd79WaZkTqEgXQFxmjGcHmsQYvH9HPLdNwSuAaGnvCLEpi9aOQlHnQmtQ7JsISWn5fSvLSurxKHeleba91Hv7odiM2HM5wv3WMToUnvFAnNV6WkBz5whKro,a0OiFhG40Bvpdg94nR4TmVllyeqUrRfiZA4CNtBOXVc0JYsTIPQkcjqeZLEkUg3uljzbeUmsTPxp4bFWRzTcMTwwvbaCQvcFb5PVdH3EmnTmLi6a7eNDKRTSoFQsCdafSrD7fXaK0FPNY3rXYq5PaoEBaBdtj3zitRwMo2PbV7KYCoGyvOVfRAD1ceCOaSvrZU4MSvvLCPhak1FiVyECu4UVJ925uvwBBlZuLrs36FRgiJEW4JoWiWO5UPuhovCP,pl2YpTitrM4UC0BUmpGqsb7h1G8yex2PcZERczqjOZ3FYXqJL0qBs2OSmIMfiDfQVhUyAPIbZKWGGIs0WdeOFGrIv08hO9w0SIAnWbc7YCql8kdCLWTaxWqJQpVHuT3CJwEDT3eUIv8Gb6bD7nCkEQeOtp5b5oRUxplvtLXk1MHecHRGm7XKRLV3bNZAIyfn8DqsfJAIvpmPZ7O0loiCz0U3uQzbXIAHDLhZAe0uLUnDW4pKGnS2ZwVQ1aHHRNOg,iRZrnU31bfZgoqZJ59TYgMeIeQhAC1ITvkH9DlmCS0J8HFSZQ9h15nZARH8pGWvLe4Xhcq0qGo6E62MJv4t5Ulaz9mETJfl0RMWDLG88t4Ahn89igPXF06qmQWyNlDRMQJfdXqtX07G5X3mdr8qXecHdSfavbvLbEd0S5tdaPyrEMaJJLNT2J5gYvwjNKDyRObGNRHJKea9wEBByqEmis18xoToOFZVUYl6JWg4mRYoge9DDPGkFxbD8ngnNacsb,2BpiNkjzFLrrxMbluUTi1se4mwyc6EY5ydZD7RW2tUgygAB0AwpLpDT4yZAfa644m3aDpAHoxrRpLp6yNKdscGXLNxTDNUce85PcuUBHzWKbwlMy2dRwqUKydfuMc7IvToKsCGRtlVcWhxX8AP1mngl8ktAd5DqkqEcWdm77Phkq5pJAkIMdfknmvMWakqxAowXpeuQCFteg2M2LqAQfHiZWsZjBI4sYej3gV8GmD5IwyHtiMxD9MwHgth2NDgI4v08pH33W1E99AaIQb6zjAWRRmEpr3GVfX2UifS7xj7clZO06T4MSoomBdAqrexkvnMLjfDaChT4CV7RDyigy6zPXc2irC5bqEoskN771GGKuBfT5MavBQNcD19U6TwcUwS5K5e2ec4uD3U18zfVibXUTRPO5pWthWBnzUDETkBU0MyeEOFWR6BvoGKmRxKUJLRXt7mdslLFtEs9KLIL5Of6eo17quq9F8ggRLq9js7tr1zY8m8laPnyW0ohtpYlF,oBmaUB5dhdb7ts4vhtA96ikrFVcvk5Azgw2rLdxrpP34o3pD4Aht1RvtzvQNBT5yyIMMnr2xKBuwQym8Nc95NuoSK3JRg2SlAB2D0EtnkwPrGdyG9hjlbjJhR01ewaFrhZiPbni0mqQijSwA1SerXvGtMSc8TKookR4VVDoTD1dcQzM4uIDAQqHSRqqwZiFkRQT9xxFT7JDLzfUVTsRHSlQJwuGMUWmj2qVCAOKsy7qtfk60A4f4qL3uGL346d0J,58zm6RsFVP2Hd2Xc7qdl1pOWuW0yddylqq68AZKlQhA4LVazGSARQ5b9f7AZmgZUW9bTonE93C4mZP6azoXLzzeJQysoXLqx8zyyJ8EY6uAyBOXzAKYGCwFzCCa2xhP1i6jmWtQ3tcOWvEZvhCx22ZYqebLuuVD23MvcOrOi5pzAvGv1rLiQ5JXckeR2cTZmyVeDYa9Lk57SMa7Hfr9D5MWknnjrWdhqAjpUIOKVEumh6fhUoxNA3VtZVwS0x3ta,qRDqkdyZPxGakwuyzvCGWV1MhkSvA6Lddzd2SLKolJLwZovyfLYT7413Y0uE8rkSedpilLUoTtCNCBnYVGH80D8S3PIGaesEnS6DBb3jJfEG9J1ODuIZL3GzigHPhHHMkZ1fwZyUabK4hOqw2KYbCdjDmkcEMikINuXiTlW6ISUtD237pPe8un3NkulFUj9C2fa9cD5N5revTO7mEZ5fDZWHiL5CrPVoSaDRdojPMWVUZicXoRRKFK2wOJxB9MrI,QCLEAMdNlcfk1A337hWAzCjTnGT4ABb1elBUQYfCcILyvynVRuPNsJ7oUwGx3AViIadXealdzTJnEd7lNDL6HDy6GxV2z5ts7Xz1D62BEViiuw5pmHzm4oqRuSDWD38G9iFoaOz9vmGqJcmNDXdjYHsRXZXcZaXLQdkC2mNwINiofxbnUdi5ZhflaSD6G5n705yIktxbbcxq3PXygXBJ6Yb4ylVIhzQs6NiSXUuRnT4ME6lN9of7kBMbST4UKlvZ,ltAhS3qrG5gOQbpwVuAbWudhO8x5GpqiX04XCTqXV6xpQYQBFvLrlogBrNuJlwxcsgYy4usOYbGErZd0MG5ytqMM50P01h8dcnyd2qkPPycy9E9GoGVgLkDNFh0F8kw8jhcyZMJiws31oRhKfqFLULMM1m29S0h9cGBNNhg9MAMBRHDgJ5zgcOLuCYR54JXqGGDz51QEFkHFIqgnZblznCoJN0WG1W9279BLIC5juHEJdfCJeGnDL90wI3ulqilc,UlW04SIVC7NiZ9zSCS2s6q5PaTN4eV2FUPWOSWLMu6aZx7rroEuuEYoi73byu1F8wTFXmdaoc8ygJCjhbI7zc52vKQ5FMXh0vsphGUFnOenFapvwDaDJkvqb8r4Au8Lbt9WKiGyLHG2FQczLMMa9wB9TiGzkdbVMBNXGJe8BSz1fdktMnGn3MZoLkzFGhmSUXmzJayyAALi3qyubIuFi1ec29QRLMzV02gUeI4oIItevaWZ40BzjfSVmIZcccrJY,HbMLXfPd5ttg1P3VsVzMuJHKCJMu8jPgwA3dKVkQUAaIn8WT1BQjQbCzJnQeoEZ9DjtV0MmEZg4Vy2vzVVY1wkgfTLa0riJ9I9F0KfY0tzYjwcJ8wQvNczjlbKZFiRqLkR0J08iLtSeREeqFCjby1ELmwA7Gt1xeH8TwX3TpsMbDmlskpCzN9f42Y23WO4Zk8oE8wOC8Az3ryQlYGJlF91GTMK359ZOHvZ0yWAHKyVvnGVkJyt0QpkdIRE0WErQk,66fzVGe9fLzJMd5ruwPchGjJUefBnCpTjfC3fKrVvoPfMclBTi3neGuLWaKf4Egyq5O8b0NSd4UdqdGTIt1bfhXy9WxDEqfWQNmYMwmXttgiiEMlo2YostqCr2Z86xhysvkePpLW98gff5UwDkd3YFgx4PmfRhYux3ImAr9vb0YEGOIpQnMmLc8X9Aefs6Hlms6Vz3AYCeZBtzEUOmFxSha49Zoc6WoMO84gTbVJZu1eELv6RhtBaFrdLEAQF58o,qzWULJzTwfuSF1hVNMGblsKijTNcnbrb8noOZnQOKLfKlmlKg4JPUMKdf1foMWP9NUeLtEjl9SnAp9LCoidBmGk81Tufwlx7dq6bGRgt8JXluXMLlbmswhEv0k0qarzIfnVnI9nbcR9c3nKUysvjz3qGFaUWLgSB4G3lrELWYkEqP2BAaifqYSFxa8pRaOgdrD5wqnK52m8OFXPFqMmHbHAvpwZFNlp46a0x7zCWPaoGbG9YHbi3ZdwomNq0thOE,zS1Ww2oBvpSflf9WewZXv2s7vLAs3ZDrNGTr6ZwzcDNzA5huUppXTfxRtrDZUoqMyZEJKjaVz1dSuE8CjGmGfqtOglh7fttvWm6vSt0zp5VGKJ50gVVhHa2rYTizYnsgWRgBk5pcjsVZLGiu58FLGWMOtmSaHHV8uB3MNbNyzLFmYYVTUsKD7ZY723xBQvYJUayy1WiuNsVoo298HxHzf1vYJEQMiwoBvDaw7QN24ulAs0QjqGHZUdzjPBOM89Cc,33faF8BI20Hu3M463s0z0hlTcZ1m5ntgRlnOLF7vXE2RO8kRqHNepK7t4AHFPdTmfvDUjO6CoNqwDv4qw7ZmPX42xVqgtTUmfHARF3TjLOergSO07NBAQ9JaGql2QRbuvKVn7MMFaYA6BGSKJwbiV1OoRwGKa7oBQuskafHCkaBay1VT4tQ2n7641claGEb6xffqZxGsbaX1yPLFj1MggGaMyf4Vo6mMD0xkieEOCiWJxSImaGFRaWklh4Fyv71e,oK26i5ptplVVR3O0DDjcZsvGstvZlgVMW7GcTOKHvW9qNTjTMC4avRtzhVTEFl0sMzmJ6Ob1tipQp9yB8jmX1M0iAeBPYWq2jXtKSn5chZ8Yquq6h1QU0tM2WMXJjzb976huRMkK5cuVsZmGisMqSvMGy57xFVXmbycvTvcI7FTCdqsPJy58uNPFV1om6h4V8oYxCS2molJcLUXrfms4L5Nf1jUxDvXnV3gGRiYCgx1iXdgLNvOrV11BcIp9WuR4,itMxgiZ9x1Tes11hd1NzsO8Vp6aWtT9mYqua9YpuZnMvouPqMzHXU0JquL50R5sy8NiUw1eaHQwjTyIBucySh4DXbXLUUAKYFbFmDowrTyi6b4gPMfRrIOQEwpkayfM7k7VnN6nkBR3XSg7cC3Irni7UNWBWgwpxnnyFDMnkSkiqbL3EuGOuYajY4yOaZctJ1iMe90N71FUetiYWNxGDWuaGGJp2GMEe58GxgwUbR3hLs8CYLKzXftbAf7FXj9GF,q2ZfPtFz25lm5h0O37qL8PKkSof9NvRXwj3ljbhN7e7GKqT7q1XdR3alnBrkm78KGRV2SlAeCfH9qZOoqgMB0ZTLfdijdd1XH5ar5a2Jel9nLqh4lC2yGZyZCQPtOTmmowxr9QMJH0Lx9bmJsbIy8wwaIu6XVV8JprWhSYT6u2q9CjAZo7qpmHSedtdL1wPHo8Z7DriuPPVJsgLKzHTpJk36Pw4MsjU7epP0UY1IsV55aizuEdlRBFsQilzMtzWB,At2rFHMf83CDOjsltr0Gj1ZPzNiiYm9miIsMuO2LP6NuhUHxG9Acry88WsUuVFItIvGNzFLt00G4XBq1q30KuTFtQno4ks3Hlu43Err4yOB7Na8mtkT0bHKg6g8Vup5qygw9SPmFFQcIeZ82qUNaGg7iu1qKBy3uRqgxetdCMLK6bCZ7KpcW6docLzWyDUqlzVF6XtD2H9hCP1voNA2e3ScFRrR14vADPGaPeqTrvERY0Rubl31tJZrbdFQjst9h,47awJ6xDgMIoVUOTaqUmnwVKAqcl3lFYRl2tnig7w4J9Jlm4AQ4vuuuCWiCUBnQE86JBmXA5QVcOPH8oS003nC8euyIbrAUgRexSFP0hsJlZnRawuyjk2rNGqVAkOMBFOSv9OCz9tVuKRRypQ2VbCSgwObmIKPcqzl0al23ccKlWLyWPnY6kK2clt7enWXhl8HdJTQpII1HPZNUpKEYOqZ0SabU5e83Gr4lRqsLJftbNP4geQ1kEEOMmhNdJFUBK,JO2Q6RvC11N6acxPmdc2eO1n3X9PJM42plArCPaEpPdQPgHaO9T0R3BbmkkUxrF0zBqFSGf0Bn49G304Uu0dlfWC7wpPcl5yNnhYIyZaN7w0IlJ9HyY2tkzdZPdGwV1bs4iz4k0QfycjSKo4Z45CZFQLwBplAyP9W3X4wiHICvpr6csPInrnJ2CEKFFBjAL6aFFvRLcV2pGo51pE7faP46fp2GVl5SY1JnQG7EvaWC49pvsJ05LH7nvRJiUyybF4,dKuPZH1H3NBg2wPh1cMswIQdYFRg4Zt5HrxoETXKBLOWOmtPc4M8EZyNd0lR39X2qbEUAPTskcwsiZBkeCP4qksjYlJIBcJCKq3d3yndrATg4wlyaqcwVmJgJPiTIRapftt9Hiyai5Tc1xYWlmt2fX6av36uG5CfBJK9PcFeXNlRspydnA83N4R5fpYnZnVt6d9yAqeZLEJAQ67P0aJ8ESALcMVGW7yL2NfSCdOB9ORAQ4wKBV97gbQ0BCwahNTc,6enCXsWRGWS4tVQ9aluLi4Gy3lvbRjfD4WKhLsAnl4rpoLvGO52NW604Fd3K64ERLhTV1cUuEPiulkXQE8OCRhcRgdNmnUeCqEJ5ZgahUiHZwNhFR0wbgwuBo98ajFpmfYgndekxHXqxIobS51SmEaAT0Z600DLZlcTXkCxN8HqBgvbFnN1acBbHW0t4JVA1cAmzfSMQidV2zytxCrVWDsKfRb2ZdZ34W7J3bX3bA1rZk61YCTxg6nDQaoRRxa4d,HxuFsRlY80sBUAyDnyJnLAAAQhI1VmqE7O0Ar858f7ytXSSoxxoJj6CYBvY6PdZfMx1wPL364OAVRNG4zM79dvSnH0uqK1vNXXMw5IRjF7QAJSFSxzWmxZkP8zdz6FH1oaIVdsnhmeBON4b2oTiwT5uFxlK6OC03iCwLX3pToZ90nyaDYPtg9h8YxO4HUqCQ03fdV4nT8oHqaDaI0eHJ6yzBnJyViuuSfQwePaWf0ZLSjDR88CMgSKyjJbNwAELe,KIHneba6bhJzSkKhr7IHAROia5UAjcxJNHItTBYTgv5SyS99HL1bUlRNqAdnwDtzym9BhuPxB3gREwLWOUAfTds21BPf55d0tQ5AX7AeB4q0I3R9z4075wgeiRF9iB8hmLrQPJy0Ic1lURKzyMgc970H0GiNtrxAdmSzCZkrahxDQ8W03oBljXmi25jZWtQGTKssAYFaK5WMgviaMQYhj1HfilpvINQWVcVimPYHccYch3qYHDsU3ktffNWuF8KF,EdHRpRYhUbwZTd64tXQe0eLVOQ7JKUoO1697iEdwkTUcMWopwMeOFadWY6ufR9EW6FSInS3X7M5Cdp3GqNRHaRmn2XnO8COAFL5E5NFcMxPuVsZad3GTWNe7PTs6GN61idadPF85ofyvWUZ5HPSe8qmfl1YDMUJW7vdZEfJf8PYsxH2nwj9Z0pFZAu9IRcaPoozKRD5aefmP2DservIvWsMX3vJlpJnOcnbfGzzsAt8cqS9rKw7oyjTC7Qcrghwk,Wev7r1npVQHz6jGeVN7s1x96R9FJDdFWWUmqbauxooPu4nhyduFzP5RPLc0G7uYxIgc3z17PqmkvzVh4rPdMIhTBdktFsY9T23d2tMeuErN3U6vx6RDzAh2ebhG8W1KuX5O3aE0FodYgjrwJkJfZiRS3C3JV1XPey5haib4Itas0fhH90o2gIycCrTbwek8L5jep5B8BsXRPUfoPIaWnfGv4U4vPPZSKm13wzqB618lqREKjWq7PwRJmu4Wp2b1G,HltcUPP9fswRCKmA6hhlOfaC3SnIMd0gabZhNmLsi7EqxP6YxVp80mQzjpfMOK5xMvyq4cfrzIb133h7yxRUdBc4FZ7xH8XnB0k3tQFDCzjGwfeySfCz1FJEPCmWZ0le661O3vqrX4NDJXGA7FS2GxGQLteduNObwjJ1b9rojr27sT2Wq3eKlg41UK0DZgnSTPVWghnjCcAMpreAmVDfeWippvy79NETW7dcZv85SZmN5zbMAzzwxtLyiwOeZJIw,VNosI5u8WM1bUOjvp03AFAs4Le7shSsOeRE5pSOuP1bY0bs3myExmc3XXgwkY7sRAgxWUTA81dX19429CfWc7DI5dhrChoriII13w3p7hvfaROlBrouieqZijY2n5xvwtxTrM3iz2ObAPZWd2eJBzZB44IBZotZtHE2Vj2JCDDGSXioXrMtYAaM2V90Qyrz7JTEBSL86xCxeTOsbxD6jJ2NCu4kauteFKZUkXXQxClKm4u4wnqEkOcLACMAUhafl,uqEGYqSA5aPJJQJgWqURYT3tooU88VspL6gMUgMOc7pwke28F9h3qb1ZHTDG8vuxzuGlv5pzjCcURlFJTiF3AhVviyLXDZzxv4o9vGJRVnkbdxYEBoGphRTqcZGnXUh6cHTsN9LzuuhOojbEMjxdeL0Yzr0ohDxkhfUeDKE2AtStUsz3sY7hIjqMMSnqrLGl2ZCaaAQjW3FhbXd96zuk4jgMfwnloIG9ludKLUngo0fMOSs3HGZN1lhqljmVctdl,ujxqL66lDOtZQsZkL8VKRyxDgVZ2COamZl1rUsFg0zKPwmfxj4TBazo7mFsn7CWeatsLNlhTF7i6S72ako3IpPV2r1o1WLWaV3dr3ZJX584yr9yVx2eZaBLLW9zc9eR4GFFE8z0b9GGsa8nU4bz1M8cb0wYjcbWrLC6ZdGyBbe5TdOWQJLWqyZjNC1qHdWEr9vPN5liY2cVUCDP73xwLQ5jiUhgHzSM0NLsRYrtQbm6lk9NsX0CVOWTlOud5e4yN,1qMwtZYF0SDEAP9piK6NdgAJEMOgcW7muqzSYdSTTkYvebnWlPaFDnaUqEefBSsZno5IMGabvZOA65Lgx5AGHFfr1UAp0aRzVxRBsWi1NeK4Z8t87ca91FvdLX53Eflhi6mIg43OfBga5TtbdcWu4uWwJlZtZmG9lxu8HdwwMhenqnOO3712x00p5vJCSqYZmzwT05cwVe78QSBDslCrxZ0b85sFwilkdr57aQP8qulOs1u4265VMagILVgpHuRg,fhFK1BAKC87LSEkCQ2RzIln0xX7XCmMJ0sW3P2vLfsqK5MTgI8EQcxI5fCTFEJkJQL614RaoiAxtaClCpPp4MvO2wb8aAVBLP5zjFYAIGk361tU28iMA2rP1mybeMU6eF6NHldsG69ALsY44ldYnIOYsNPask40FkFlH7WItrMNfHpwMMxEzFJjyQNDi8WMc36H62w4zmIFjdlubiWC8MMEXuYTZRiSNuLYeSMss1hs83FpaPuxPpgLuwDPVS070,bACfxAJQIlFVOyyapTZUEgnplf8RluKYxNkd2c4fD89yNgNgRDD5L4Gvvzo6QnaWIKtjorMGkf03GGd4IP7z8W1JIFsOVby0HPTOr1kX5Wqp32Pjx4gwGrIq9sDED0VkCXrCP2iZkUT2QGUdy0GDp2S2CGTbmRs80u5hhbeSedKlaaSN7wNIvdhS5br6zDWMamqrpWN4rZjfAOsgo0clQDI0XI4enZr5KWoSsVpMgRaUXIYwMrVrg9ufbGVZxt7Q,8vEtFn6xrsSFzVbX0uapUkVzh1ZNkiHhyhsqG2StnqeEk1nmLU49tqzQzsGwtE1o9y1ABx3J41bk1ShljKKIXz3QuM6BroiKkdHG2c9N0isZTWarBc2PFCooUNYwKJ7Xkt1yD1365rcnPkVAK4uKP7k7L8qdsKLmh9Q3kkaHUzp6bzGX4ybYDswb746YE7SSKtJadJuZ4QnF3qOPhNMExH5FnWNHmJZHffmmLwlO1lab01GJQBljt4R3BEFYVHd4,FIM4d2rI9HCEZlA4pQHVZKiLInwo0ikVXYgqACDLrExzdB62ZFSOVdl0wZThZVM5LFNvGqXgVJxjFk5h1Mwd8OtrhOboflF0Lwd9dIVVZK5DpFgoY5tWDAhsEaaslwpa3kcfI1SmYq5Vw6iZ3aX4rMuo2WOkWLoPvDf0xPnRw5faQfJBwwjyCStLYeufHQJIXhlWndmDCqD3ONoLyxtUWouGtLbbJGNN1oB6reJzIeTv6xzgXnVaVkrmZO8SI9zf,d5WGisbgbm9IRfxza5yYhwuZEYgMpZ6DwfqliEaubn1ekCXamQDxsUlYfqUDOdmz7d5I3GHI5LwpAqb0MCtnZviKihN3CkXM3sSV8wZW1VoRqeaiapvKjA0LbWUiGX4V62wprUc8o6TlAPUJlseVKdz1hhAm9Escby8k9cs5Ki3CXKCpc4uKlMEZXwdJC9CVfK2w7M293qRo55ibTt42EcCRIRtlZRuvoKHhYBb96p3MQ3n1n34xd10e4HfjA4Xi,4NtDTOX4A250sceG0xulGSTFYYdTzSckN2RAdeLcyLvf7p2Xbm8BZmpZYqKCBkf9remL1IrQBsNnH6qSf7aIbWS1X3ZvVGFI7rlj2Jri3lJfvsfX1bps6EZ1laC7mSMJO06BCJu9Evx391ML7MeIj3256HnBFX09k94MZwmNjdWqDrfyDNkHYjlaTF8tx47j1mZ7SaoU9BWLuie2pg07aiekWOI3uzsvxv9T3lWu2PL8qSC8uCC11KjqMVRVw3Ed,DHBRESKlcR6WHDLcDyAzALFzSTambvqWftW1SKmAwUd7RNscXUAZ2Xe6EDwGJjyPLH2FjhGRLOH2VOBLdvbwm2rlAB3qbRXXzwiDR6GoXIl3Nxh98pm3PlEqbLjDOn5Z9Aq0N9wOmUH3PqmDUqFoE51C9hPGKoFLBpKLqz3epWiQusIv2OVZ4J0xL4hYYgHDhIjN70p3H3h9XSHlzFFI1ZK4WtSCF2WbZREbDcprTLnCZZJEFeaQz8sWvJJe50vW,E2tQs5oinhchD12PJfzkOQuj0xpiGF3l2U6yHcyF1M9uK9obrsIY086BwpNTeU3mCaEku3MTUSS8M1zvV5reBS1QoIdjceE5AHTEJUXRfTMsE2fr0J5ILRze1rTVzLaHCPMbEDnZQlbqdIXqcB79SOxnZj5DpHnax5WqIi1k4gsQi7CzEHUw6mEO69uLyg9FUXFzbimLtKjb0DgmyiMZiYdkTQjMwSNtUTdA6Gi6hl5RacQlmmaHKIPLwIUkutuV,wMN4Xm08bwtYP1PMEdVPhuvOAZryub1VHGqBrn1hxam1QwnWChKrzNdhgzPwfCSG9lxNxdL7yLWDtxaYdfZQLIvdfHJ9dsON12vyLaiFa6hwglHhf7PefINd0cv69yScYBCDLoEqNYLJh8lYZeMBgqjQTIyaGUgxOwOfyIqkFZojF3JGiuU8q52z63MGsn4G2BDVtgxHaBXl5URM1z1g7uovpCi7W3vWWFOWmQaQsp9ffle1bCAtL3BZwaWpN1Or,cE7qBo64o7F4nuZFeRYATJCEp0Hvb5ZVocvLlFZjileRjHTmy1gRbx1guULIQMfcJg2sThgX9RKOIUVPbqw513WtLEivhvZh2CU8S5YPT9nfGv8H5qZDciKqftNcSRUGjGBjT2ytvr8oojxNdmCdIj62bxjrFCq9XDVL8WpT31QK71iKctKU66tFN9MnIsgobBFEKQVxOK5cTpmSxofQDfPbfhXbZnkVwWtYoQ3aXMehtnpgBTLhN8pVLQErjsg3,QXeqYJZrH8UCWTiYZqmFZO6zSDlZfh0DKUEolPcbbSUqXDyUzRod55t7ud6U60PuDzbxsS9EuugYJTw3MhefRqv01mkH8INnyUYBmP38QvYtxoih7cPaXaL1mEAK8l6zoZkYOIHyBMjNaTaSvok7UcD2b1ZTN3HNa9SLIl3vYsjC35jFBdYHVKE3LxyUVnKsi2y3943EhSrRD8MJqiHRBHW7BOXNKYiZPZV8Ub2cd93hRyzOZnupzI6IgNppXKxw,gtuIeNSJsluUOPQjYFRU1OJw2QNmybEyjPjJycEzqQTWLttR9pUTxtplbzWJxwcok9z4sDSYnoJyQSMeH27oarq2OHCl7QkW6bPaNYb7IgtWzL66S9EznQK9CJDDwDfdlQofc4yZF8sTkfLSDLujusP2gaupCGNRjYWyMxyP1cZxuBMYN7v9cLpAJ0awyskRZP40AVFdqPXm5AI6yuMk4wTR59LJX1SLLszPmD85QXQpsJNj753WcDgEFnr5LWst,hFTvccRkMsB7DPcij8DaKdhGP6n5R4xYvlI0Qn1X8rxlhgHP17lPfTQc4pbhwtjmFUmS8hKGRBIQB4QYdnsYR4B6K7xEco1kYigHLxykLsaS4BQfinG5dIuNCVi9ZCB465VAAQJSWj1v8vpGQjdqTdVAbpYZ2L1P4j1VswacVi5n7pRphPDXhZ4uZl3ZJpvvB2sPVwU7uLGM42x7YhtcimSdRBXAg2NQJekbqG3AxuWsrr2TkvTLbNGrYKBQvghh,Ai2QMaUKfYk3dKiB5aEPNVPrDQ6hYdNJK7FclZnJptGNlf1LA8wyQ9mVGADeMd7nBYMQvnqDQRDL9abZAytumr0X5ywV5VeY9be5RbM2pAxj1O9LtrRA5qNsuoFzVNsxZVxiJdgNG9jk1gWCnwawucZcGWXlQmQ6NAztqdo6viYWselFf8JtwRvch2j2kfdE19v454yzWpgRlBRSiA7vg3irqaXrop1UAPau3nxDWpZZpN3o0H1sv9Zl80H23M1P,RB0WWmCqaGRfra7bw4DD7SkKoD7ANEiieRG5EHxpGqTAPgJ02FjUUybAhNwDh6PIlIBqQN9irUpQI4WSLe8sjScDcnYo1BklyYJ1TcbOLqhIGTTrx0WbHqRPyWs6i2ZrDJZrXbN5Qa6raySkC9WfCZOEigJncL9Q8dBZWwVVrazNR9FP9RZ2uPJpQRwP87gnqrZYK3x2yFoJlaVz57KbIfVXhvGFlAVYwlkHzaN8EwSd9sTahUE6xHZikwhJdJg9,RCN6bu5opXlZffa8sNeU8WFX4ulyaJ5gAzzIqKm9s7K7br2btwK6pby3Go0eSgPJiIj4vFPLr5GgDrOioCi4aFiPwtahIrBdPHMuu6Qn5qcSsX94pSvd83E1xXMBPTdaxcYAnhmFthgQpKtC88xAWAiFphRfhBgxNEPYD3jzsStUJSJpnVJDSyBB8EiOibmEShS5xBRv3lq7Q2AgbrbpRPFvhkNvZstEHHFODjgCv9qE7uAfKNHCozzvJee3bniy,ES4BePZXy71PxFBYvr7AUf13qelvgSRC9SBbbEaKVEUw2Ghd2Vtm8bPaRBYeUV3LERTLG0xVsiRA8VOvTYGcKo5LmPAkIgzO7qEsU3uYmwSPhMrUBB4AUv1tCc4ycDZYcBEqb66ydwcHNI7GUVlGEoHIEzfduGTfnCoUgXvXwbO2tLG579AQOXOGpeYoAOwwM6pDCw8ae41u17pYHVXHtaSsOm1pih3fMvdVzU2ZoCv19455va0OBiIeQIWvhAIj,5YQVgIvW1TgccTLk5K0ekk3RkUyU5zled8RxDifsrwlIckirciS1kUPyILnrZGZ9bAacPmN5m3IUovkOxSaUjnuFQfJvCo5ldTvdLfRzB6qzJ4rTEgsx1UW4zEojBs6EDN6Bwr1vZIgT0dXuUbFEOowdP23PGFjJ1l2HI1M63KRfhF1dZGl4joLQWXiaisCR4F1Zp9Q8ALOKLDRv2prEpDCt0YFi8jP5rNamK2dAkxvyDNXiZgSkez9tC21L7MWx,6MrgYu8AbR2tzLzH47GvBAMmqgeVQ3aey5gNfcillanUu1OAe5W0FyUz8nZxlraqNrk7I7ymaR7RnWBFyfQ0EtvNBe7CA8AitvzKoepKrfnIXJnzmENOd0xeaB4VtVc0t3PysnOiujfCDawBErRLAFueDyINf15xHKpsjTMHA00GPuhwgUbYdzEPBZeAif6lcQHXOJpq1hzjhSYThzBaZ4JEWFvkmKDR4LvWlk7oNYiHjH69r7Y4AbygHun6gAy2,QLZonM0aNxOQuH1Q2i4d1o3kfI67Y0JmXcP8OfyzTzQFvsQoLLQYW2seXmvEuL4SLRl9uXlLktXW5A2bypFO56iJStOpnQ5rt6hSRKPCUhi5d02UAGo3iGkwBS7IVqeoLZ1oBIuPIQWQFUHvAYEtnWl8IevnAbS4dqXYPIYjwTanKs73paxtdIcnFpbfwdyS8PvWRUa7766BhgTtzUqMIJ876W15cpc4gnp4JkXyx92u7IxVfTo6RmSjeucXY3XF,zjrUHeqllR2nZEN1ZiyOcQLBftytmU4cqD8srw2XfVBhLMMcY2uRuo2FKyUqtOvuUKdNj4t45zL9Vniw46kX61DA3gPNWfE8tDqiIem9OTS6UkTL9Y9TuMXqUYD6FcpCz4kKWN5nxFHxJKjrkF4E68FdAlc5uhckeevAkgj046NqZofBazmCMoM6ax7IBiMbCWPmNHUS8oOGi1L7L2BMjdgNUt6hkZYcxBshpG65WKutamMEiIfPaCye2RtVZfFS,o0xvETCeZB5lNMKfG0IuK6KKpgiog4y82lsSGiFwJ62u9XKRtubqltLzUctXNOAWVVT03EOSlkblUYS7vOGr'
2017-07-21 07:58:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
,2017-07-21 07:58:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [5, 10]
ok 102 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client dis,connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
[ThaliCore] Session.startOutputStream(with:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [5, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:58:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:38 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:38 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:38 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:38 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:58:40 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-07-21 07:58:40 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 07:58:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 07:58:40 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0484139D-6BA0-,4F9E-B15D-5ACBCFFF6C4C
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:45972DD7-E306-4909-AA0D-0C667C726D62
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55918
[Thal,i,Core] Session.disconnect() peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
,[ThaliCore] Session.deinit peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:40106DE9-C5FF-46AB-9B53-46CA9B93576D
,[ThaliCore] Session.session(_:peer:didChange:) peer:70B04368-0D4A-4A8D-9826-F72B55687508 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0B120418-C410-470F-B4EB-FEA3D7D66723
[ThaliCore] Browser.startListening
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9B670379-F421-4B0E-9E50-7194D7F30,7,65
2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
2017-07-21 07:58:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}]'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
2017-07-21 07:58:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}]'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"45972DD7-E306-4909-AA0D-0C667C726D62","generation":0}'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A567840-BD3A-492A-B7C1-9FDC148793B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A567840-BD3A-492A-B7C1-9FDC148793B0", generation: 0)
2017-07-21 07:58:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A567840-BD3A-492A-B7C1-9FDC148793B0","generation":0}]'
2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8A567840-BD3A-492A-B7C1-9FDC148793B0","generation":0}'
2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:58:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9B670379-F421-4B0E-9E50-7,194D7F30765
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:46 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6DB3860E-B90C-4A5E-BB38-7F151BB791AA
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8050E8F-A256-4C6C-B53F-1934FB7725E0", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:C8050E8F-A256-4C6C-B53F-1934FB7725E0
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C8050E8F-A256-4C6C-B53F-1934FB7725E0
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
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
2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:d1ee16cb-8b23-4c4d-82e3-405cc8cb30c0 error: startListeningNotActive
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GU3gUSc6zmqV8TzwUizJ4HpjbvII6tsb","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"d1ee16cb-8b23-4c4d-82e3-405cc8cb30c0","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"d1ee16cb-8b23-4c4d-82e3-405cc8cb30c0","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4FDBCF44-7C7E-4BF7-97C1-B7E10C729258
[ThaliCore] Browser.startListening
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FRXDpbnyCwBIyzF6RRNRZEaXofFfix8y","error":"Illegal peerID","portNumber",:null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 07:58:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6DFD8A48-B1A4-410D-ABC5-E464FAB93F3C
[ThaliCore] Browser.startListening
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:4f8b88e2-9390-4abe-b58e-9b1d1e306a49
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
[ThaliCore] Browser.startListening
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
2017-07-21 07:58:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6197B4A3-B151-412A-B001-2B3152ED3D6D","generation":0}'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6197B4A3-B151-412A-B001-2B3152ED3D6D, (syncValue: LizxSQS269r07LwktYwW0YO4SZjVQbbN)'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152E,D3D6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84BF45AB-2C17-4C8C-9041-D9E809F54A9C","generation":0}'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55927
,2017-07-21 07:58:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LizxSQS269r07LwktYwW0YO4SZjVQbbN","error":null,"portNumber":55927}'
,2017-07-21 07:58:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LizxSQS269r07LwktYwW0YO4SZjVQbbN', error: 'null', listeningPort: '55927''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0) found active relay
,2017-07-21 07:58:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aJYJr2J2ZPp4lhXcxTrFV6Dfj813G4i7","error":null,"portNumber":55927}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0) found active relay
,2017-07-21 07:58:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fYPcz9PTmllufAJAGOhzesRftVWG0L7c","error":null,"portNumber":55927}'
ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [5, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
2017-07-21 07:58:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A
[ThaliCore] Advertiser: session connected Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A
[ThaliCore] Session.startOutputStream(with:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [5, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
[ThaliCore] Advertiser: session connected Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420 state: connecting -> connected
,2017-07-21 07:59:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:59:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E
[Th,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,aliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] Virtual,Socket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [5, 12]
,[ThaliCore] BrowserManager.disconnect peer:6197B4A3-B151-412A-B001-2B3152ED3D6D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55927
[ThaliCore] VirtualSocket.closeStr,eams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] Session.disconnect() peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [5]
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-21 07:59:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
[ThaliCore] Session.startOutputStream(with:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [5, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
# teardown
[ThaliCore,] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [5]
,[ThaliCore] Session.session(_:peer:didChange:) peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] Session.deinit peer:AB22B73A-1A68-45CF-A1E7-0BF6FBE95420
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-21 07:59:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 07:59:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'listening 55932'
ok 149 Should throw
,# teardown
,2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 55934'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 55937'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 55941'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
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
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'listening 55946'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:13, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 55950'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 55954'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 55958'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 55962'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux ,- 2'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
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
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
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
,2017-07-21 07:59:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 56014'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 56018'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 56021'
ok 196 port must be in range
,# teardown
,2017-07-21 07:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 56022'
ok 197 second start should return same port
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'listening 56024'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 07:59:18 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 56026
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9A958306-EC3D-44EB-89A8-EA859D70CC56
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:468EE149-B728-47C9-B180-34D960C,0F8FA
[ThaliCore] Browser.startListening
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 68CF2D20-4470-42C1-86DD-5C4B66AE0A9A (syncValue: dm9o3AwWXT0hmpV5grJetPFC9VZFF0np)'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","generation":0}'
2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
2017-07-21 07:59:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","generation":0}'
2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:20 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,8CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748
[ThaliCore] Advertiser: session connected Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1015D93F-E501-4227-8F24-53E16A8BE897
[ThaliCore] Advertiser: session connected Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1015D93F-E501-4227-8F24-53E16A8BE897 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68,CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dm9o3AwWXT0hmpV5grJetPFC9VZFF0np","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dm9o3AwWXT0hmpV5grJetPFC9VZFF0np', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF4A1875-D77B-4930-8496-4BFA2D99D970 (syncValue: yc1ejR7tkXF59MLDQvHFeL1vDU9wABY8)'
,2017-07-21 07:59:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:59:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1015D93F-E501-4227-8F24-53E16A8BE897
,[ThaliCore] Session.session(_:peer:didChange:) peer:1015D93F-E501-4227-8F24-53E16A8BE897 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56036
,2017-07-21 07:59:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yc1ejR7tkXF59MLDQvHFeL1vDU9wABY8","error":null,"portNumber":56036}'
,2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yc1ejR7tkXF59MLDQvHFeL1vDU9wABY8', error: 'null', listeningPort: '56036''
,ok 210 should be equal
,2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BE7D46BF-E36C-4CFC-8F1B-0419EE18E394 (syncValue: ZYz2Nquu8wfKnC09kOrg3mHZ0HE0TcZm)'
,2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56040
2017-07-21 07:59:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZYz2Nquu8wfKnC09kOrg3mHZ0HE0TcZm","error":null,"portNumber":56040}'
2017-07-21 07:59:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZYz2Nquu8wfKnC09kOrg3mHZ0HE0TcZm', error: 'null', listeningPort: '56040''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9A958306-EC3D-,44EB-89A8-EA859D70CC56
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:BF4A1875-D77B-4930-8496-4BFA2D99D970
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56036
[ThaliCore] Session.disconnect() p,eer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:56040
[ThaliCore] Session.disconnect() peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListen,er.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1015D93F-E501-4227-8F24-53E16A8BE897 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1015D93F-E501-4227-8F24-53E16A8BE897
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 07:59:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:1015D93F-E501-4227-8F24-53E16A8BE897
,# Multiple local http requests
,listening on 56042
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E
2017-07-21 07:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:32, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
[ThaliCore] Browser.startListening
2017-07-21 07:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-21 07:59:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
2017-07-21 07:59:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","generation":0}'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BE7D46BF-E36C-4CFC-8F1B-0419EE18E394, (syncValue: n0tvtM4Oxdo197yTJhsvmEY09ZgWayUV)'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE1,8E394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","generation":0}'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
2017-07-21 07:59:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFCB2BCD-C807-439B-8959-5A1DEF10A145","generation":0}'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", g,eneration: 0)
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BE,7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BE7D46BF,-E36C-4CFC-8F1B-0419EE18E394 error: max retries exceeded
2017-07-21 07:59:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"n0tvtM4Oxdo197yTJhsvmEY09ZgWayUV","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:59:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'n0tvtM4Oxdo197yTJhsvmEY09ZgWayUV', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:59:42 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 07:59:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BE7D46BF-E36C-4CFC-8F1B-0419EE18E394","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 07:59:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:59:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BFCB2BCD-C807-439B-8959-5A1DEF10A145 (syncValue: Vr8k6Ui,ddfvZAG5cWHYf6oYpKRxsZn6f)'
2017-07-21 07:59:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCB2BCD-C807,-439B-8959-5A1DEF10A145:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:59:42 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 07:59:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
[ThaliCore] Advertiser: session connected Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56060
2017-07-21 07:59:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Vr8k6UiddfvZAG5cWHYf6oYpKRxsZn6f",,"error":null,"portNumber":56060}'
2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Vr8k6UiddfvZAG5cWHYf6oYpKRxsZn6f', error: 'null', listeningPort: '56060''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 98432C64-BBE6-47D0-8F65-58905E66E920 (syncValue: VVBaLUIUVZocDRDISA8fgsNwtKsgBHfb)'
,2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
[ThaliCore] Advertiser: session connected Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D state: notConnected -> connecting
2017-07-21 07:59:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
,[ThaliCore] Session.session(_:peer:didChange:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56066
2017-07-21 07:59:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VVBaLUIUVZocDRDISA8fgsNwtKsgBHfb",,"error":null,"portNumber":56066}'
2017-07-21 07:59:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VVBaLUIUVZocDRDISA8fgsNwtKsgBHfb', error: 'null', listeningPort: '56066''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:59:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C7BBE235-3DD4-43E3-BA80-A,3BA3281F60E
2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56060
[ThaliCore] Session.disconnect() peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
,[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", gene,ration: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:419DC82A-44BA-4B39-B3B6,-93BAD8E5056D
[ThaliCore] BrowserManager.disconnect peer:98432C64-BBE6-47D0-8F65-58905E66E920
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56066
[ThaliCore] Session,.disconnect() peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 56070'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 56071'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:67B0FF51-8558-4DED-AF70-911363BEFBA0
[ThaliCore] Browser.startListening
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
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
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 56072'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3442C328-6B73-4C8D-8594-2F7A3D69F77B", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:3442C328-6B73-4C8D-8594-2F7A3D69F77B
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:5,9:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3442C328-6B73-4C8D-8594-2F7A3D69F77B", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:3442C328-6B73-4C8D-8594-2F7A3D69F77B
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,7-21 07:59:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3442C328-6B73-4C8D-8594-2F7A3D69F77B
[ThaliCore] Advertiser.stopAdvertising() peerID:3442C328-6B73-4C8D-8594-2F7A3D69F77B
2017-07-21 07:59:53 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
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
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 56075'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:53 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
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
,2017-07-21 07:59:55 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
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
,# all services are started when we call start
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'listening 56076'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F1D856E3-157A-4E8A-AB20-3DEA1793CA3B
[ThaliCore] Browser.st,artListening
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0A6F5C90-5B72-4CF6-A369-11E0F80594D4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,0A6F5C90-5B72-4CF6-A369-11E0F80594D4
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:55 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0A6F5C90-5B72-4CF6-A369-11E0F80594D4
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
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
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 56079'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00B2B1ED-053C-4795-B2ED-33AC1D5EF4FB
[ThaliCore] Browser.st,artListening
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE9CFF34-CEFC-4251-983F-EA8BD5242B74", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DE9CFF34-CEFC-4251-983F-EA8BD5242B74
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DE9CFF34-CEFC-4251-983F-EA8BD5242B74
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
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
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 56081'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7AE23EAA-D2E8-4EC4-BFD6-7D2BFFCAFCE8
[ThaliCore] Browser.st,artListening
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DFF65872-42C2-49E2-9711-CEA98D9B429F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,DFF65872-42C2-49E2-9711-CEA98D9B429F
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:56 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DFF65872-42C2-49E2-9711-CEA98D9B429F
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] B,rowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
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
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 07:59:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
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
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:00:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
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
2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
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
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
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
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 08:00:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 56084'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:797823E4-9DF0-4ADF-9A91-39E34561B15A
[ThaliCore] Browser.startListening
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: ,'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 56085'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4218E910-3D38-4833-85F5-B4B11E5F29B2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4218E910-3D38-4833-85F5-B4B11E5F29B2
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4218E910-3D38-4833-85F5-B4B11E5F29B2
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 56087'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'listening 56088'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:874187AB-2E37-49F9-BEC8-0D087CCED10E
[ThaliCore] Browser.st,artListening
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A8CD3A1-17EC-4D75-ACC9-498530804876", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,1A8CD3A1-17EC-4D75-ACC9-498530804876
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1A8CD3A1-17EC-4D75-ACC9-498530804876
2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 08:00:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:00:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'listening 56090'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCE26EE8-3CFC-48D6-AB96-3A21F7FD9086
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 98432C64-BBE6-47D0-8F65-58905E66E920 (syncValue: xlmtF60rGcuoIirVcfPbQdmwlCvsjMNa)'
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
2017-07-21 08:00:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}]'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F
[ThaliCore] Advertiser: session connected Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}]'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F
,[ThaliCore] Session.session(_:peer:didChange:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F
[ThaliCore] Session.startOutputStream(with:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [5, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,8432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,8432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,8432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:98432C64,-BBE6-47D0-8F65-58905E66E920 error: max retries exceeded
2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xlmtF60rGcuoIirVcfPbQdmwlCvsjMNa","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xlmtF60rGcuoIirVcfPbQdmwlCvsjMNa', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:00:24 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:00:24 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 08:00:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 08:00:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:00:24 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9476F58F-47F8-4A4C-A0A0-0319CEDF586F (syncValue: iG9fhG31vAD9mye2fxqmcXNrq1w03H5j)'
2017-07-21 08:00:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0,319CEDF586F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
[ThaliCore] Advertiser: session connected Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56102
,2017-07-21 08:00:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iG9fhG31vAD9mye2fxqmcXNrq1w03H5j","error":null,"portNumber":56102}'
,2017-07-21 08:00:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iG9fhG31vAD9mye2fxqmcXNrq1w03H5j', error: 'null', listeningPort: '56102''
,2017-07-21 08:00:26 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [5, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:27 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:27 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
,[ThaliCore] Session.session(_:peer:didChange:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
[ThaliCore] Session.startOutputStream(with:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [5, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:00:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:27 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.d,i,sconnect peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket close,d by remote peer})
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPListener.sto,pListeningForConnectionsAndDisconnectClients() port:56102
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID,:16
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.disconnect() peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
[ThaliCore] VirtualSocket.deinit vsID:16 [5, 15, 17]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:1,5 [5, 17]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [5]
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Session.deinit peer:DABCA13C-E1C4-4520-9ABE-F4325694BB8C
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 08:00:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:00:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:00:29 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
ok 293 error should be null
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
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'listening 56105'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 56106'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4E745B5-6C70-4822-845D-4789020AD752
[ThaliCore] Browser.st,artListening
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:00:31 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAd,vertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll ,called on server'
,ok 310 error should be null
ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 56107'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9256CCFD-0E00-499F-9AE5-07B67527BD74", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9256CCFD-0E00-499F-9AE5-07B67527BD74
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9256CCFD-0E00-499F-9AE5-07B67527BD74", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:9256CCFD-0E00-499F-9AE5-07B67527BD74
20,17-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9256CCFD-0E00-499F-9AE5-07B67527BD74
[ThaliCore] Advertiser.stopAdvertising() peerID:9256CCFD-0E00-499F-9AE5-07B67527BD74
2017-07-21 08:00:31 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'listening 56110'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 322 error should be null
ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 08:00:32 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'listening 56111'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:00:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:00:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 08:00:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e6702e80-4015-4037-9dc6-ddc3a5338375","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e6702e80-4015-4037-9dc6-ddc3a5338375","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
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
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fe08b251-9812-497f-a529-0b0f4d8df5b3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 354 peer should be ,available
ok 355 cache contains native peer
2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fe08b251-9812-497f-a529-0b0f4d8df5b3","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e05af3d2-f9cb-4ff6-a8dc-eaa3a0df6f85","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 peer should be a,vailable
ok 363 cache contains wifi peer
2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e05af3d2-f9cb-4ff6-a8dc-eaa3a0df6f85","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ecbcbf86-7ca8-4ca7-b99f-40003ed007d1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0862ed1f-64dd-4689-a616-8cc32abee782","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 370 second peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ecbcbf86-7ca8-4ca7-b99f-40003ed007d1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0862ed1f-64dd-4689-a616-8cc32abee782","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d3f6f8d4-456a-4d49-8b03-0851232a07d4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d3f6f8d4-456a-4d49-8b03-0851232a07d4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 08:00:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 08:00:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52086fa5-065b-4ae5-97f5-fb21d1ffb5cf","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 386 peer should be available
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52086fa5-065b-4ae5-97f5-fb21d1ffb5cf","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 387 peer should be available
,ok 388 should store correct generation
,# teardown
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52086fa5-065b-4ae5-97f5-fb21d1ffb5cf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 56112'
2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab2eb38d-010c-45e8-89bd-c45de0c3852a","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab2eb38d-010c-45e8-89bd-c45de0c3852a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered corr,ect peer
ok 395 got correct generation
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ab2eb38d-010c-45e8-89bd-c45de0c3852a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 56113'
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1444ad2-6d7e-49e5-904d-2e0c073f50ae","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered available peer
ok 400 peer is available
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f1444ad2-6d7e-49e5-904d-2e0c073f50ae","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1cdbe549-3da8-40f5-801a-b6bdcb7a77fb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1cdbe549-3da8-40f5-801a-b6bdcb7a77fb","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'listening 56114'
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2936be74-d0fe-4d8a-a1a7-a6fc86e4b5ea","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c77e2009-96db-4615-bb45-ddb4a9d9d10b","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c77e2009-96db-,4615-bb45-ddb4a9d9d10b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
ok 413 it was wifi peer
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,P,eer {"peerIdentifier":"c77e2009-96db-4615-bb45-ddb4a9d9d10b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 414 we found peer again
ok 415 it was wifi peer
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAv,ailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c77e2009-96db-4615-bb45-ddb4a9d9d10b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,# teardown
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2936be74-d0fe-4d8a-a1a7-a6fc86e4b5ea","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 08:00:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'listening 56115'
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3352e6a4-89cb-4c2a-8ed8-09c817872b0b","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7720ff80-b539-4536-a1f1-449f258e72da","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3352e6a4-89cb-4c2a-8ed8-09c817872b0b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 426 peer became unavailable
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7720ff80-b539-4536-a1f1-449f258e72da","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 08:00:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
,ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:00:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46836f06-43d1-4f41-9a95-abfceacb8501","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46836f06-43d1-4f41-9a95-abfceacb8501","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46836f06-43d1-4f41-9a95-abfceacb8501","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46836f06-43d1-4f41-9a95-abfceacb8501","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46836f06-43d1-4f41-9a95-abfceacb8501","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-21 08:00:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 462 contains expected properties
ok 463 the same ho,stAddress
ok 464 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 56116'
2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acc2d248-7a1c-4648-b3f1-b36c81499fbc","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"acc2d248-7a1c-4648-b3f1-b36c81499fbc","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 56117'
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3005c0ab-c6f1-4175-9e82-ec5be20bad05","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:3005c0ab-c6f1-4175-9e82-ec5be20bad05
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3005c0ab-c6f1-4175-9e82-ec5be20bad05","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 08:00:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 08:00:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 08:00:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 08:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 08:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'listening 56118'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB48C05E-4F64-495F-B090-731E5939A27F
[ThaliCore] Browser.startListening
2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1f6d18f0-0177-498e-a387-1c91434f671d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a17feab9-356b-488c-b499-93be2d007f97","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1f6d18f0-0177-498e-a387-1c91434f671d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a17feab9-356b-488c-b499-93be2d007f97","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}]'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'listening 56119'
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dc681c6b-2cc1-451f-8aac-28d1aac0cf28","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"349db6a2-d160-4221-a48f-1580bfd10c36","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dc681c6b-2cc1-451f-8aac-28d1aac0cf28","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"349db6a2-d160-4221-a48f-1580bfd10c36","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:00:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'listening 56120'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1AEB318D-F436-4ED2-92B3-8595DFA2FFED
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Browser.startListening
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}]'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 98432C64-BBE6-47D0-8F65-58905E66E920 (syncValue: 0)'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}]'
2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","generation":0}'
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:00:46 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
2017-07-21 08:00:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","generation":0}]'
2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
2017-07-21 08:00:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","generation":0}]'
2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,8432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
[ThaliCore] Advertiser: session connected Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,8432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
,[ThaliCore] Session.session(_:peer:didChange:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
[ThaliCore] Session.startOutputStream(with:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [5, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
2017-07-21 08:00:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
2017-07-21 08:00:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}'
,2017-07-21 08:00:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:00:53 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7ACAA28D-9E95-4685-A1D8-2D2948F6818A (syncValue: 1)'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
,[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CE14C4,33-882F-4790-BE2A-EEC0450765EB (syncValue: 2)'
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765E,B,", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'handleP,eerUnavailable - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:00:54 - DEBUG thaliMobileNativ,eWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7ACAA28D-9E95-4685-A1D8-2D2948F6818A","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] Advertiser: session connected Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B17D840B-525A-43E7-8097-00BD8B450B10 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56130
2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":56130,}'
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C39D4A68-9FE6-420E-91C5-1FF6CE30E22A (syncValue: 3)'
2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [5, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:56 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:56 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
,[ThaliCore] Session.session(_:peer:didChange:) peer:B17D840B-525A-43E7-8097-00BD8B450B10 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] Session.startOutputStream(with:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [5, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56135
,2017-07-21 08:00:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":56135}'
,[ThaliCore] BrowserManager.disconnect peer:98432C64-BBE6-47D0-8F65-58905E66E920
,[ThaliCore] BrowserManager.disconnect peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [5, 18, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:59 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:59 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-21 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CE14C433-882F-4790-BE2A-EEC0450765EB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1AEB318D-F436-4ED2-92B3-8595DFA2FFED
2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-21 08:01:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08,:,01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:01:02 - DEBUG makeIntoCloseAllServer: 'clo,seAll called on server'
,ok 527 error should be null
ok 528 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeS,treams() vsID:18
,# setup
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [5, 19, 20, 21]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] V,irtualSocket.deinit vsID:20 [5, 19, 21]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [5, 21]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [5]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 08:01:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
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
2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 551 Size must be 1
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
ok 577 Size should be MAXSIZE
ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 581 Size should be MAXSIZE
,ok 582 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 583 Kill should be called once
ok 584 Size should be MAXSIZE
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
,2017-07-21 08:01:08 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:01:08 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 08:01:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
,ok 601 is an agent
ok 602 enqueue 2 worked
ok 603 enqueue is not available when stopped
ok 604 start action is killed
ok 605 killed action is still killed
ok 606 enqueued action when stopped is killed
ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
ok 609 good enqueue
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
,ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
ok 618 we are in the pool
ok 619 We are out of the pool
ok 620 Action was killed
ok 621 The original kill was called too
ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
ok 624 first kill
,ok 625 second NOOP kill
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
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-21 08:01:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
,ok 643 Got another null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 649 should have gotten null
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-,07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned ,successfully from start - clone!'
2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 652 Yup, another null
ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
ok 669 Second does not throw
2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-21 08:01:16 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 08:01:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 08:01:17 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-21 08:01:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 08:01:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-21 08:01:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-21 08:01:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 08:01:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-21 08:01:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 08:01:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 08:01:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 711 should be equal
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
,2017-07-21 08:01:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
ok 720 should be equal
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
,ok 729 keys match
,ok 730 secrets match
,ok 731 We have an entry!
ok 732 keys match
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
ok 740 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 741 should be equal
,ok 742 peerDictionalty contains 2 peers
,ok 743 bluetooth peer's notification has correct connection type
ok 744 tcp peer's notification has correct connection type
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:01:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-21 08:01:33 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 08:01:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-21 08:01:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 08:01:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 08:01:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 08:01:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:36 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:01:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-21 08:01:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 08:01:40 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 08:01:40 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-21 08:01:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 08:01:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 08:01:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 08:01:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-21 08:01:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
ok 775 Public key matches with the server key
,ok 776 hostAddress must match
ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 08:01:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 08:01:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 08:01:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
ok 794 should be 204
,# teardown
,2017-07-21 08:01:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:01:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:01:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 08:01:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-07-21 08:01:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
# teardown
,2017-07-21 08:01:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:01:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 08:01:54 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
ok 813 First stop and removeListener called correctly
ok 814 first action kill called
ok 815 second action ki,ll called
ok 816 first cleared dictionary
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
,2017-07-21 08:01:55 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 08:01:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 08:01:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 08:01:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 08:01:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 08:01:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 08:01:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 849 Got, error as expected
,# teardown
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 08:01:58 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 08:01:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 851 Got error as expected
,# teardown
,2017-07-21 08:01:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:01:59 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:00 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-21 08:02:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:02:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 08:02:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 08:02:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:02:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 08:02:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 08:02:12 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:13 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 08:02:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:02:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-07-21 08:02:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 08:02:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
,ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:02:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'listening 56262'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Browser.startListening
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:798FE329-CA2C-48EB-8C64-3BEA2692A145
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
2017-07-21 08:02:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 4)'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Advertiser: session connected Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
[ThaliCore] Adve,rtiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: notConnected -> connecting
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56265
2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":56265}'
2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Issuing ,multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 5)'
2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365,-4DBE-9591-19F3D61E10A8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] Session.init(session:identifier:conne,cted:notConnected:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [5, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Advertiser: session connected Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [5]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [5, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [5, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [5, 23, 24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [5, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [5, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [5, 23, 24, 25, 27]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [5, 23, 24, 25, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [5, 23, 24, 25, 27]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore], BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [5, 23, 24, 25, 27, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] TCPLis,tener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:27 [5, 23, 24, 25, 29]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [5, 23, 24, 25, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [5, 23, 24, 25, 30]
,2017-07-21 08:02:28 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] Session.session(_:peer:didChange:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [5, 23, 24, 25, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [5, 23, 24, 25, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56279
,2017-07-21 08:02:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":56279}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [5, 23, 24, 25, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [5, 23, 24, 25, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [5, 23, 24, 25, 30, 31, 33, 34]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [5, 23, 24, 25, 30, 31, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [5, 23, 24, 25, 30, 31, 34, 35]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [5, 23, 24, 25, 30, 31, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
2017-07-21 08:02:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,0 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,1 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [5, 23, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [5, 24, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:24 [5, 25, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [5, 30, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [5, 31, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [5, 31, 34, 35, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:39 [5, 31, 34, 35, 37, 38, 40, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [5, 31, 34, 35, 37, 38, 40, 41, 42]
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [5, 31, 34, 35, 37, 38, 40, 41, 42, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [5, 31, 35, 37, 38, 40, 41, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withE,rror:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEnco,untered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler ,disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [5, 31, 35, 38, 40, 41, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [5, 31, 35, 38, 41, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [5, 31, 35, 38, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [5, 31, 35, 38, 41, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [5, 31, 38, 41, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [5, 31, 41, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [5, 31, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [5, 31, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [5, 31, 44, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:798FE329-CA2C-48EB-8C64-3BEA2692A145
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:02:30 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-21 08:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:02:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [5, 44, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket ,closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [5, 44]
,ok 867 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [5]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'listening 56294'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Browser.startListening
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:713A7165-53BE-4979-B6FF-1B1C4676AEBF
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
2017-07-21 08:02:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}]'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
2017-07-21 08:02:32 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 6)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":56265}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A,8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [5, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 7)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":56279}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [5]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:ni,l
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [5, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 8)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":56265}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [5, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:49 [5, 48]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 9)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":56279}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [5, 48, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [5, 48]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket erro,r:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [5, 48, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [5, 48]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Session.startOutputStream(with:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,2 [5, 48, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] Advert,iserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [5, 48]
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 10)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":56265}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [5, 48, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [5, 48]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 11)'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) found active relay
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11,","error":null,"portNumber":56279}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] BrowserManager.foundPeerH,andler peer:Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7FE17ECE-9559-451B-8C09-,89E0B0DFA7BF","generation":0}]'
[ThaliCore] Session.startOutputStream(with:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","generation":0}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","generation":0}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7FE17ECE-9559-451B-8C09-89E0B0DFA7BF (syncValue: 12)'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] VirtualSocket.init(inputStream:outputStrea,m:) vsID:54 [5, 48, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [5, 48, 54, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [5, 48, 55]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:55 [5, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Advertiser: session connected Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Advertiser: session connected Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:56279
[ThaliCore] Session.disconnect() peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:34 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-21 08:02:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0 state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCo,re] Browser: session connected to Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56306
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":56306}'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A74787B1-5250-4D60-858F-332648519D4E (syncValue: 13)'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7,4787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Session.startOutputStream(with:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [5, 48, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [5, 48, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Session.startOutputStream(with:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [5, 48, 56, 57, 58]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [5, 48, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Session.startOutputStream(with:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [5, 48, 56, 57, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Session.startOutputStream(with:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [5, 48, 56, 57, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [5, 48, 57, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [5, 48, 59, 60]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [5, 48, 59, 60, 61]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:A74787B1-5250-4D60-858F-332648519D4E:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,60
[ThaliCore] VirtualSocket.deinit vsID:60 [5, 48, 59, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [5, 48, 59]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [5, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56265
[ThaliCore] Session.disconnect() peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", genera,tion: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3BC99E38-DFA3-444D-847D-9,34C08CEAD4F
[ThaliCore] Session.deinit peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}]'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:02:36, - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A74787B1-5250-4D60-858F-332648519D4E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56314
2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":5631,4}'
,2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 14)'
2017-07-21 08:02:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":"Peer is unavailable","portNumber":null}'
2017-07-,21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:39 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB,5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 15)'
2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E1,0A8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:02:39 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"gener,ation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [5, 48, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:62
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:62 [5, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A74787B1-5250-4D60-858F-332648519D4E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [5, 48, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [5, 48]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
2017-07-21 08:02:40 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}]'
2017-07-21 08:02:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","generation":0}'
,2017-07-21 08:02:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:02:40 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FA,1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,A1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":"Peer is unavailable","portNumber":null}'
2017-07-,21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:41 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FA1EB5BA-D365-4DBE-9591-19F3D61E10A8 (syncValue: 16)'
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", g,eneration: 0)
,[ThaliCore] Session.deinit peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":"Peer is unavailable","portNumber":null}'
2017-07-,21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:41 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:72759949-905B-4F26-99D5-EC97C00BEAC3
[Tha,liCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:713A7165-53BE-4979-B6FF-1B1C4676AEBF
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":false}'
2017-07-21 08:02:41 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-21 08:02:41 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerUna,vailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:02:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:02:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdent,ifier":"A74787B1-5250-4D60-858F-332648519D4E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB,5,BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FA1EB5BA-D365-4DBE-9591-19F3D61E10A8","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:02:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:02:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:02:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:02:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.disconnect peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8
,[ThaliCore] BrowserManager.disconnect peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8
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
ok 877 (unnamed assert)
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
,ok 883 should throw
,# teardown
,# setup
,# Test TransientState
,ok 884 should throw
,ok 885 should throw
ok 886 should be equal
ok 887 should be equal
ok 888 should be equal
ok 889 should be equal
ok 890 (unnamed assert)
ok 891 (unnamed assert)
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
,2017-07-21 08:03:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:08 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:08 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:09 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 927 verify failed
,ok 928 constructor called once
ok 929 constructor called with right args
,ok 930 match start arg
,ok 931 start called once
,ok 932 stop called once
,ok 933 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-21 08:03:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 934 verify failed
,ok 935 constructor called once
ok 936 constructor called with right args
,ok 937 match start arg
,ok 938 start called once
,ok 939 stop called once
,ok 940 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 948 verify failed
ok 949 constructor called once
ok 950 constructor called with right args
ok 951 start befor,e stop
ok 952 We got at least 3 calls to start
ok 953 at least 3
ok 954 default 1
ok 955 1 run
ok 956 default 2
,ok 957 2 run
ok 958 default 3
# teardown
,# setup
,# start and stop and start and stop
,ok 959 start out null
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-07-21 08:03:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 968 verify failed
,ok 969 constructor called once
,ok 970 constructor called with right args
,ok 971 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-21 08:03:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 (unnamed assert)
,ok 976 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-21 08:03:16 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 977 verify failed
,ok 978 constructor called once
,ok 979 constructor called with right args
ok 980 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-21 08:03:16 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-21 08:03:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:03:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
,ok 987 Got right error
,# teardown
,2017-07-21 08:03:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-21 08:03:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 988 Got socket hang up
# teardown
,2017-07-21 08:03:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 08:03:20 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 989 Got 500 as expected
# teardown
,2017-07-21 08:03:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-07-21 08:03:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-21 08:03:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
ok 997 revs are equal
,ok 998 should be equal
ok 999 revs are equal
,# teardown
,2017-07-21 08:03:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/8,0C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/80C72E26-,F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 08:03:29 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-21 08:03:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/80C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/8,0C72E26-F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/80C72E26-,F190-4527-ADDD-9CE44F459DC4/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-21 08:03:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-21 08:03:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-07-21 08:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1004 failed due to stop
,ok 1005 failed due to stop
,# teardown
,2017-07-21 08:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1006 should be equal
,# teardown
,2017-07-21 08:03:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-21 08:03:34 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
,ok 1007 Expected bad seq error
,# teardown
,2017-07-21 08:03:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
ok 1009 Timer was cancelled
,ok 1010 should be equal
,# teardown
,2017-07-21 08:03:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1011 One go and one blocked
,ok 1012 All blocked
,ok 1013 Still blocked
,ok 1014 should be equal
,# teardown
,2017-07-21 08:03:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1015 We waited long enough
,ok 1016 should be equal
,# teardown
,2017-07-21 08:03:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1017 Should have gotten same timer promise
,ok 1018 Still same timer promise
,ok 1019 We waited long enough
,ok 1020 should be equal
,# teardown
,2017-07-21 08:03:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-21 08:03:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1021 expressPouchDB was called once
,ok 1022 expressPouchDB was called with 2 arguments
ok 1023 expressPouchDB was called with 'PouchDB' as 1-st argument
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
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:46 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'listening 56388'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E0084094-3592-4581-B88E-078991AC15B6
[ThaliCore] Browser.startListening
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "51D6A431-3F75-4911-BD7F-575A42D1D949", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:51D6A431-3F75-4911-BD7F-575A42D1D949
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 08:03:46 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:51D6A431-3F75-4911-BD7F-575A42D1D949
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
,ok 1062 ThaliMobile.stop was called with 0 arguments
ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1067 expressPouchDB was called once
,ok 1068 expressPouchDB was called with 2 arguments
ok 1069 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1070 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
,ok 1071 PouchDB was called once
,ok 1072 PouchDB was called with 1 arguments
,ok 1073 PouchDB was called with 'dbName' as 1-st argument
ok 1074 ThaliSendNotificationBasedOnReplication was called once
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 56390'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC56C79B-E80A-441E-BD0F-04AA7BA0AC97
[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C3D36BEA-53A1-43F2-A646-AAC8B1690709", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C3D36BEA-53A1-43F2-A646-AAC8B1690709
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1092 ThaliMobile.start was called once
,ok 1093 ThaliMobile.start was called with 3 arguments
ok 1094 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C3D36BEA-53A1-43F2-A646-AAC8B1690709
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:03:47 - DEBUG thaliMobileNativ,eWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 56392'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9D2B1355-C525-4AAD-A785-3C96B867E0E0
[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8FAEEAB-35C0-4741-8C71-F66F660CB151", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B8FAEEAB-35C0-4741-8C71-F66F660CB151
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
2017-07-21 08:03:47 - DEBUG t,haliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B8FAEEAB-35C0-4741-8C71-F66F660CB151
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:03:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","generation":0}]'
2017-07-21 08:03:47 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A74787B1-5250-4D60-858F-332648519D4E","generation":0}'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 56394'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CDFA309E-C1D2-416D-90FB-72AEC0ECB993
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4463B790-CAA8-4207-B927-9B8722F3A2A9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4463B790-CAA8-4207-B927-9B8722F3A2A9
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4463B790-CAA8-4207-B927-9B8722F3A2A9
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:03:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 56396'
2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:08DB726C-8A99-441B-8F7A-B7F500BF1EE2
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52102B8B-1826-407B-A4BA-5ECAE66BD712", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:52102B8B-1826-407B-A4BA-5ECAE66BD712
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1113 ThaliMobile.start was called once
ok 1114 ThaliMobile.start was called with 3 arguments
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:52102B8B-1826-407B-A4BA-5ECAE66BD712
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:03:47 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Session.startOutputStream(with:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,4 [5, 48, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [5, 48]
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
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result:, skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 08:03:49 - INFO Coordina,tedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpoin,t,Reached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOG,GER result: passed - test defaultAdapter'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwar,ds'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 08:03:49 - INFO Coor,dinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-21 08:03:49 - I,N,FO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-21 08:03:,49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - test sinon sansbox stub'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-0,7-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-21 08:03:49 - INFO Coordin,a,tedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
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
2017-07-21 08:03:50 - DEBUG CoordinatedClient: 'test client succeed'
2017-07-21 08:03:50 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-21 08:03:50 - DEBUG CoordinatedT,haliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
