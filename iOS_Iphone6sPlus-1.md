#### Test 11335185132a4422_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5CDC05F8-222A-4FD0-B55F-F3CC4CFB741A/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/5CDC05F8-222A-4FD0-B55F-F3CC4CFB741A/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185132a4422/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54060"
,(lldb)     command script import "/tmp/5CDC05F8-222A-4FD0-B55F-F3CC4CFB741A/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
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
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:17:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D6E0006-8052-42DF-A1,B4-2328EDF26E1A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2D6E0006-8052-42DF-A1B4-2328EDF26E1A
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D2A8A38-4E6D-4C13-A37A-A7C3F58BE69E
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F73D1E0-,88D2-406C-A389-C0589D58A255
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1FD278B0-4E16-472A-B8B0-65E37207EAFC", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:1FD278B0-4E16-472A-B8B0-65E37207EAFC
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FD278B0-4E16-472A-B8B0-65E37207EAFC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FD278B0-4E16-472A-B8B0-65E37207EAFC", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-20 20:17:26 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.495711982250214
,2017-07-20 20:17:26 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-20 20:17:26 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1FD278B0-4E16-472A-B8B0-65E37207EAFC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1FD278B0-4E16-472A-B8B0-65E37207EAFC", generation: 0)
,2017-07-20 20:17:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 20:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 20:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 20:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 20:17:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2017-07-20 20:17:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 20:17:30 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-20 20:19:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-20 20:19:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-20 20:19:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-20 20:19:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-20 20:19:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-20 20:19:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-20 20:19:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-20 20:19:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-20 20:20:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-20 20:20:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-20 20:20:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-20 20:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-20 20:20:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E159D9F1-1A65-4884-B8D3-D2AE21B76EDA
[ThaliCore] Browser.startListening
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73DD01FE-C3EA-4494-9F93-E710C57CB8BC
[ThaliCore] Browser.startListening
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:22 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "527CAA90-9617-4B66-9C60-E55576F24623", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:527CAA90-9617-4B66-9C60-E55576F24623
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:527CAA90-9617-4B66-9C60-E55576F24623
2017-07-20 20:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:22, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1EE0211C-94DA-4B3B-BF7B-8A6544E4F063", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1EE0211C-94DA-4B3B-BF7B-8A6544E4F063
2017-07-20 2,0:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdver,tisingAndListening(onPort:errorHandler:) Peer(uuid: "1EE0211C-94DA-4B3B-BF7B-8A6544E4F063", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:1EE0211C-94DA-4B3B-BF7B-8A6544E4F063
2017-07-20 20:20:23 - DEBUG thaliMobileNativeWrapper: 'dis,coveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":f,a,lse,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUp,dateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:20:24 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:2,0:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1EE0211C-94DA-4B3B-BF7B-8A6544E4F063
[ThaliCore] Advertiser.s,topAdvertising() peerID:1EE0211C-94DA-4B3B-BF7B-8A6544E4F063
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:24 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:20:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:35 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:20:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:20:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49A3ADBD-7079-407F-91ED-5D6A5267C170", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:49A3ADBD-7079-407F-91ED-5D6A5267C170
2017-07-20 20:20:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:20:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:20:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B4936033-B56A-423B-8E8B-FBFB78573B6E
[ThaliCore] Browser.startListening
2017-07-20 20:20:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-20 20:20:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:20:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A3ADBD-7079-407F-91ED-5D6A5267C170:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A3ADBD-7079-407F-91ED-5D6A5267C170", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAB1F9B1-62A3-4E4D-A23B-B0D4250937AD", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:20:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:20:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:49A3ADBD-7079-407F-91ED-5,D6A5267C170
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:20:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:20:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:20:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E842B187-8856-4931-8138-58CD7DE0DE5C
2017-07-20 20:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:02, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-20 20:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53BA5DC0-4C93-4712-8931-AB49CAF9A5EF
[ThaliCore] Browser.startListening
2017-07-20 20:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-20 20:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
2017-07-20 20:21:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","generation":0}'
2017-07-20 20:21:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D80EF86-38E0-401A-9B97-EDC2B291AD62, (syncValue: xCcJFuumn8tIzos1SxiIDsFZClyZsEbF)'
2017-07-20 20:21:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B29,1AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:551CCA29-3144-4F99-8F62-23A17B5EDC77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "551CCA29-3144-4F99-8F62-23A17B5EDC77", generation: 0)
2017-07-20 20:21:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"551CCA29-3144-4F99-8F62-23A17B5EDC77","generation":0}'
2017-07-20 20:21:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:03 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E842B187-8856-4931-8138-58CD7DE0DE5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E842B187-8856-4931-8138-58CD7DE0DE5C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54491
2017-07-20 20:21:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xCcJFuumn8tIzos1SxiIDsFZClyZsEbF","error":null,"portN,umber":54491}'
2017-07-20 20:21:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xCcJFuumn8tIzos1SxiIDsFZClyZsEbF', error: 'null', listeningPort: '54491''
,2017-07-20 20:21:05 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-20 20:21:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:E842B187-8856-4931-8138-58CD7DE0DE5C
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54491
[ThaliCore] Session.disconnect,() peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD
,2017-07-20 20:21:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFDDBCF9-F546-460C-848D-F0AFC9A5,8FC0
[ThaliCore] Browser.startListening
2017-07-20 20:21:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:21:07 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:07 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
2017-07-20 20:21:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","generation":0}'
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D80EF86-38E0-401A-9B97-EDC2B291AD62, (syncValue: Zu0coQX08xalfUNuQYjVq67Ca6NJuxfk)'
2017-07-20 20:21:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B29,1AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
2017-07-20 20:21:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","generation":0}'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
2017-07-20 20:21:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","generation":0}'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4D80EF86-38E0-401A-9B97-EDC2B291AD62", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4D80EF86,-38E0-401A-9B97-EDC2B291AD62 error: max retries exceeded
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Zu0coQX08xalfUNuQYjVq67Ca6NJuxfk","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Zu0coQX08xalfUNuQYjVq67Ca6NJuxfk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4D80EF86-38E0-401A-9B97-EDC2B291AD62","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 56B307C2-08AF-4A29-8560-B6A8AFB389FF (syncValue: b9SYq1l,uQnNfUSFuXDbAYUSeP06cKBGD)'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56B307C2-08AF,-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:21:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D80EF86-38E0-401A-9B97-EDC2B291AD62:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949
[ThaliCore] Advertiser: session connected Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42690737-DEF7-4FCF-A261-1577781FF856
[ThaliCore] Advertiser: session connected Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42690737-DEF7-4FCF-A261-1577781FF856 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949
,[ThaliCore] Session.session(_:peer:didChange:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54498
,2017-07-20 20:21:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b9SYq1luQnNfUSFuXDbAYUSeP06cKBGD","error":null,"portNumber":54498}'
,2017-07-20 20:21:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b9SYq1luQnNfUSFuXDbAYUSeP06cKBGD', error: 'null', listeningPort: '54498''
,Connecting to the localhost:54498
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:54498
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949
,[ThaliCore] Session.startOutputStream(with:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 88 got the same data b,ack
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,# teardown
,2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-20 20:21:21 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42690737-DEF7-4FCF-A261-1577781FF856
,[ThaliCore] Session.session(_:peer:didChange:) peer:42690737-DEF7-4FCF-A261-1577781FF856 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42690737-DEF7-4FCF-A261-1577781FF856
[ThaliCore] Session.startOutputStream(with:) peer:42690737-DEF7-4FCF-A261-1577781FF856
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-20 20:21:22 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3,
[ThaliCore] VirtualSocket.deinit vsID:3 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,2017-07-20 20:21:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54498
[ThaliCore] Session.disconnect() peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42690737-DEF7-4FCF-A261-1577781FF856 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42690737-DEF7-4FCF-A261-1577781FF856
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:25A0073B-349D-4353-B5F1-CE7DA3435949 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "64B848E4-E7C9-4327-AEBD-DB9B9D26A8DD", generation: 0)
,[ThaliCore] Session.deinit peer:42690737-DEF7-4FCF-A261-1577781FF856
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E56D8C9C-324B-480C-8DDC-9842424945C0
2017-07-20 20:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:24, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:062AEDC2-8073-412A-9807-7AE05470E560
[ThaliCore] Browser.startListening
2017-07-20 20:21:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-20 20:21:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
2017-07-20 20:21:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","generation":0}'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3A9FFA67-FA8F-41C8-9E42-58712C34BE48, (syncValue: zOIN6RgeEBajYTd8kUNoQOGZL97qQGNN)'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C3,4BE48", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"56B307C2-08AF-4A29-8560-B6A8AFB389FF","generation":0}'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E56D8C9C-324B-480C-8DDC-9842424945C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"17C71F8D-4817-4678-B647-BED88DB07F70","generation":0}'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
2017-07-20 20:21:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","generation":0}'
2017-07-20 20:21:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:26 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:21:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3A,9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:56B307C2-08AF-4A29-8560-B6A8AFB389FF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "56B307C2-08AF-4A29-8560-B6A8AFB389FF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3A,9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3A9FFA67-FA8F-41C8-9E42-58712C34BE48", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3A9FFA67,-FA8F-41C8-9E42-58712C34BE48 error: max retries exceeded
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zOIN6RgeEBajYTd8kUNoQOGZL97qQGNN","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zOIN6RgeEBajYTd8kUNoQOGZL97qQGNN', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3A9FFA67-FA8F-41C8-9E42-58712C34BE48","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 17C71F8D-4817-4678-B647-BED88DB07F70 (syncValue: uk6rVV5xsdNqGUHKxrWgpr3ajxsSIdM4)'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17C71F8D-4817,-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:21:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3A9FFA67-FA8F-41C8-9E42-58712C34BE48:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] Advertiser: session connected Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
,[ThaliCore] Session.session(_:peer:didChange:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "17C71F8D-4817-4678-B647-BED88DB07F70", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54508
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uk6rVV5xsdNqGUHKxrWgpr3ajxsSIdM4","error":null,"portNumber":54508}'
,2017-07-20 20:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uk6rVV5xsdNqGUHKxrWgpr3ajxsSIdM4', error: 'null', listeningPort: '54508''
,Connecting to the localhost:54508
,Connecting to the localhost:54508
Connecting to the localhost:54508
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
,[ThaliCore] Session.startOutputStream(with:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
,Connected to the localhost:54508
,Connected to the localhost:54508
,Connected to the localhost:54508
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00 state: connecting -> connected
,ok 91 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] Session.startOutputStream(with:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] Session.startOutputStream(with:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] Session.startOutputStream(with:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 93 correct string length
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: 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,L,zyWnChb84USRPeCu3eEVCpJAu1FOWErU1sQRwtpOafxFpFt7cVtkXDhgdp7r7sbWfet3ySh381ST4IEBerM59Y6UkLef7IpGxXvnI8epcGeNMdqteNYmZ1kYXGgrhjco3m47KISY5cdHiCtnO6w87NL794IwDOHlflhgQfMCdA0QxrLzWgQj6wI8rLRzcQpCJ0WtXc9rBnIZmaDm7lZlPfMUpV0yWagbDaflV2xsEaypewkHNgInTHJMQ2Ue7oXU,UUB3HwNgY6FhnDZ7dZk7uZFymwdMYQPVjIV1Op9KWs4nxRYkYvkhkSG1XIdPEgoNlDXwUv5TpLfe7dBx4hGxfEVIBkh3o05yQngDm887WGoIYGqJ5bszlEZrfLy2qICAtLfMjoKJod3G3H09ev3d0ApsSUf5nkjcOachunrW6rCTx3rZODqsvlbwZJEyWJj2ru6uzbRTwiBhmWE4HTBnW7cYaNy56EzDknZlY92DAQX7ueWo97TWItHlEDeWXFl3,70XQZHWo3nyMOnPE6dR8x52sIAzupSDIwE6bFX7zhC90ynFf7yqxRaAvsOyat09FI1lPTEgSNHO6HFLmxydeVhQBbTBSN3zqemwGUy4PvxRxkVmO6hI7cXfFaJI13WVVkGdER5gsf5FQ9VgH1BTT7zFFxFeNb5e3pJyYx3HlcgEKXY92g4A6VPQ9sBcMkioDI41HG9gZ39fHpHzG7SkZkE4yHe5c53KhhDIvAUI18shdaCA4XPTRZtw8E3WtCyqg,lRoqLsOCRcnC7Co1wbhG8sxQLF4bhagqSi6FccIGcNeR6cyNNmr7A4CdSu9HYyWfBTgEFUNQ2TOHrDiRgbRg1vUnbDMSj3aolZ57XlOXNLCmdy1tPGalaMWmo9vyzi278dQHYLWR7irCLR5JTPYoxU2SsOPYoECBoY6TJGrv7waK2kThuS9yyrp20P6S26hkxfbTGtCGLyw4vjD5znXUG728SiDOTadCEMGeQSuSgrPaodiLU6inF4rHjIVgFuq,y,d9cDCR0WvFn7rTfJdBnzNr6W7MZwvlDi3BkS2cotSB8234bhUNPuLzY1HPPRjQLXnRg8uomAFRGKknnSgDjN3b7LVuGvBeeQAAeQqSzx8FasAEzpj0J0VutCND3PoVCMQmNiZIeIQieduZprbOMall8Bf9zmcMl8cm7MEuQiKG8cK2DJR47Jl7cqffb1toppaQEL1H0bDJFz6eu9oXEtS7ImHdNtkTj887136t0VegHbRGa1StDEa1NshMYfMxIPJbN4Tmg8aaDISK2lKk95zjB1Qz5u2TYbfPjpPcu0BLUquSAhDOlfNIqmPZ5IWz498XMOknNsDyeQ8LqwjxNDgU517N2i73ofIt1jLfK2d5NiHpdmR06hhk7MR7RWuqqPNGd5TWeZztJH2wqtPvNdC6qOtsOv8s1sjkZjQ1lKoaRTOjOTQUJvsBPaTUtjP7Ht1uPkrwmqlyzDRG2VEMA4dkewhoctzSAGGzM80yfg80MLY1CkpcpPDdlq0OnRBNKh,KeZHnUjhjiZ52ZJDAOrI1ad93mbFs4WIayYoTtUl4HXfCWgkbT4rrRM4UwyFWkLWAqaqgBiuxhvf82EZGHp33t9vGRQ4taJTiOS9xtaSZ8VZI85jueIcZJVl5KvpJlmZ4d54hsSqvav5Pel47u1Qe3tlHIjHlNsThcaioEKTlw38xP6nj63ibQ0bk8L8Uyl6AFtqcir6ZHxrkxOJRZhtza0sTk4x9p4nplK9pOEeCBaLOj3u2O4AMYiZGemQm4Ce,CsBaZU5N5v1Q0pcwwpzAkAvtacxmuzipNybIrYqiJahfjFt6KkuXIuwMXL7OVMFr3eVgsICEstpjKmnAfclVgBdVvAPrM9p5QbUqDmUXGCRQvXbMR5KD6wG8JFC1O6il3on0NbpSbwzJv01O40IHRFVvoTU4RgTuuqcPiXn1SyTU5iyv8g11F0SdaUp25auowOTnWNHSo14xLrvIYOmFrNrjIFwwGki3N90V1LnZV0nToHdqZiVS2anAAkTmRwXP,vLx1nGF96cl7d6EkIWqM6E2rVt5VJ6dZ2obvXg3gIV2U1gQBOUA0sJs0HEW5kJorxI1eWtiRi5wtE8hksCI75Wj6rXugoi8mW7INXi2Oecvz7eykdHInJGzK1coJ9JSZYG8dew0gidpw8LsL5QqrimTBiSg2oMGCiE2hgTRFtA2x5WksudDm9ItYDm5WxNaa6pFucnsYS8OMOWdttymSFVpmwyMEhkewaZB5zHtvPDCbq7RClX7NGnLuPOfO1agi,9tfxrPRUSa5dZNd9Zdf41MKhELXR1T7Ifs1ysZveOXtTwJFfOI72rOkvM611Y75AGGlF9oER3fxWHxZmsciUD58lkntRpvJl47j9llPfpDYIM1UzBFtvES7UvVmI66SionOmKu85uBkZRwONpGnDlwcBu4T8fLPUPRmkaxPAdB7HOPBaOLNPFFKaIgpoS3RK4vdmUTBxDnLyWnhUih95RvJIjRYa6VLxdLOWLrh76HD1jMah58DBDwJ1jLoAVyU3,rBOTYcvCFPtDWXP02R7rr4qlxcnfqsN2F7nmOac0FstKQVWoo4Mg7ZzL4VC0qDceomW9ENDF2k9NrNcaOXRRsXaLS9H2YCWIkUsHO7chwk8BLb5AW7FOLsUh9sczYegA3bK4Vk3Niar99kl3Wbs5wxFnlEKDsX7hDysTZdkm07Cv0ZytMrTJByqwYIdpTIo1RBG6Mt0WzDykDIsXxAZIQhFDgRcUMDjctkkCnFE7tSnbFk4FItUg77rPK5rRsW0b,KNKOx2bzoDS6wwSeCLAe9p3Tbj34XW4Hc537g9rtmiTLQXUvxxdZYuh7vl6dSbZeTemRZyr4TuufP4uZtzZNNzkozhHYfKSj89GeEzop8tjE5L1HXu5kPwgvweiSYWPQ3amCTOoEi8LnFOW5DJfo9vSflCxnE6yp2ffNNhkCZvvZyyztZhYWAy3wtrzG66APP8amtnwgaQzgO80eCtddMryu2gq3Mgg0ZzsvlKny3YytTkx3Zjf5BtbTnITZRnpl,12eJxI4eey7KxwYiK06C4MOijP0xm93rrgXzY4O8pmxVof2HslbZz2fs7AW8vPjdQhShhZIYFs3Ugxwoo7XJNHEWrWhgwEi6xUJn6cn8oK7QyQpClNvPz8JnOvOleTTMBqhdXEFLlbBjSFnJFlI7Ya8wlZFt8ZYR4841KYysfAFFu9RuWFIWlI8HXODyrQLV1PLCRICEoeH8M1AFeoYdu8hpZSXZBZNNENbz9ZZjHL7uC2iq2dkmuZ93RAx2eCVH,oSdN2MwilMOp6HJpchYPeh2olCw8R16zUB6s0gKhAWQyBeYo3OomTbEYSMBoHS1oG2a3NkxJRGHcj7gXjr0d2ZIVOgtoLknm2ToSycnm74dvo9ygMqbzu3jE0lu4PLiItms8o2mD8eyyM7cFkHYLCrbixl6gK3IBkR322LEfCuOWUwVkJOjV53mPS9ysXTwqw42cODLgCo6kyChxrlDtUCq64wyuHMA1Gy0bmwyiF8D5GfP00gfNJr7j5fRDYCng,Bb2UlSmbXWfi4t6EnvIlBXXSXDRqRhvBsAR4A4TCu2OniOfm13bM1Dc1ztq5bA02gNAE4WbZPaEIebu08ZpyS9xB9YNOS55UTgi0rbTThyr4aAv50fpCk7J813BR2KxNgD2exhfJV2lRHQQpKKIA2VXIt3ayDnQSXEkGtziNZfsodn7Dk40CceuVEdzuPW3ugoihpqH2wckk08V9WtCuqTBlSXdnqLDk10Nz9lNUOqmbhP67rS1sxyLz14nZce21,qLw5iZAU9kaJYC4vuVxETBtxdKcdKbgdQXgKaxdlVLlj0YWUtsMILNpDknma5MS0ORc5Z3DD9TlNoZcbARpEtBYBNzyfDU0Ik4Uut92PBLD0An4ygybmFGV0sV14C0AGAtcEM1zoaBbAdAbj3Y8s6HHCvsdgyDkCORv0GJF8fR7WPMB09pUyCPVS8RZTo0tL5GWEbSH05d8Aw1FyaVhyAqM6XTXav10RVaGh7NbXSTbwJ3Dpv0FsXSd4DRyFBzXz,nSNapRcrASqfVkRlC5KUze52EtV9RndDeiNKEnCSIkCoOjZS2WycNey1T6Xlu9jScZEzVxIRytz2Ck1xP3SeCkTeD5I6lPVu4Wwalay9AJ2ToE5OJI7CV6XgeJbEMlxDRtSntnYgNLMjpK7ov6BhK9NOnuV21UWTtw7GAn7ckEjp7Xou2O6WTH5Y8jIyj2fAxGL3QoiUdxsvUs2GEh2WGnfgsYa9dMiTlO8wtzINb8R9YzlJ3da06fv7udyqQ0Yk,PMlbstNpQ4Axsp4bxy7k933jjVHqfjMTlmhcwwmsAqVuQptcoLiopkhWiUzOyTsIIS9Y5NArpdkL4w4XTFCTmR2maisR2xudCmFh9VOxQ1ych4FWUe8tx6z7l0KjpVihvUm7dXSaXdt76qWxa7dd1km6tnP51YuJITTqUdSxwN3wK4YIeAGmj9qMRPBLKmChjupfQ2LLYipPyD2Fv4Z3b26AucgYITxqywJPwaFCTkiPKaZL9Hn7DzuQgWVkQxM3,aaHiA6aPioNNyhuswLrgJSnV1JVJAS5yLXosHPGocYlurAtfs3m2rMFeVblW7NyECJb1TEgH1uGRPDk9bFGyDAvt96FKeuxSh20lnS3jTpsLSv37ZcyjofmOCMuPJbfeRdPz0VoN4O0uNVAoFkU7gqV5i4z2x5nhvso2WMPP6JwbF9oWyyrRwH7GO4dtc6sPaurvVmq0XT77Lpw9STj2znracY3KgReGiuzlVFbTyVguXTQ1Rf5ffR6DFYMsGnaT,aRmsExhrLisj6kZmfxuaAMNjHjHM702TLi8vucrji5tB3spn3WFJXqG19YpMZPIk7tMBh3t6Ie5KtWKedOCIHKZRi9skpX8f8ShXztmlomxP6WSeBNZE3nazGefB3IPYQF52R6tY6m4JIdRrdBin0ZU82qlE81ogfTsEcbGtXusPTF4ClvhEToGfOn3QDwTfGSUFiqoZzChPNm1VS03QXl2VramykVsDlIjAl51MEBkiC4Y2osi3ItiirP3uUmIX,Cf5m0f4Ll99Z1AaSRFSwZQ4rWDp5vNtwTJzmFmKIlccpGYvNrAKAXQHOnEWaRmRu0me9atIv3S8i1uWYp2ssCk3Jw7p4xtqIgIlK3a0aBTeIikrJpX93GuYNqvfiLfeWbXxCwDxs1W1cilTQJR8Pho11xfQhLe60jI4XGtkgiLia83qfBHyT3U8MMYOlxqgYZEHj72uabhUR5C68O5ZM7iKaBRq78mCKKY4u7Rlk4SvmfoUIjHPcY5tChw0NoeQh,xVJP7f4yIk09r7k92ifVKkzfDkf5wDOfEq0phg7N4ScDXJw0f5tmrgO116WDhuLMaZ2Q5WZP3BEE6PPBvH1S3z0bksqjhTquYq1luSvZgoon8lsJWFG5D66T6M6VPzXSZWPUTfGSjiD3govlU4ItLH2raQ2ebmtqsDAjwqHkNwyZFpyYa9mimMhJ6q8ORQwfmX02Kj3KlegMnbkAJDSjTjVE7M1SyjhOp5ADVF6E0xr1ndpbfCVNcbDsgZWzPjCxGE94NuWZsqZiY6X6txsNHTumMGTJPqLCr8CssNjsAvWHqk1YuFiGZ04a2RZ8RWBdPWqAJK5MfxbJDxMvU36Ko2DBS1PyPKvh3AOYsaLU4Gehs2FAP3c72OcyrBitlv42MP4cWy8aCAG9KbtOkbNau7Bio31758oZjRYJ9XEj0yPhkgookwQES8aLjLaJbm6zt2NMcOfbwBbPzGCWdXirlY1tikrfLr0v3LsXwY5ivN5B3pLcUzvmsMtDEnWImiak,MJbaKVy5xI96AL5pynXtpZeP0hGaUDtcJqMuYB7TJZNIl9pNHoLulRqkML1zKlzSY5mkU0AkYbysR5Kw1iXTNXD73J3Atl3b6ebK7CxBrDyV5DQ27guKpKfBx60VWoTEnuAgXwGQVDkKvHCleaa5RckPW8I194p5sEddb4sihK4RBXlzIZV7IE3mtP2CXwU9bS61ZZryQEzBcD49OHwdKfdYHrxeUTiZVU6XKlWWSwRKDZYWyXCatI4ysREX4Me,4IRhWRaQm9JZEl0o9sJRzldPWBu4etpJfsGekCbCLNZcjqrY6RcsZHdirFJvkYOob9ZGFfch1xZkJL6sUk7hcDU4owa5D4EcHgcLxyL8LJInt4A6UVuJqQfl9crJPEs3YAnXV8g8wp8UmAxhgVE6SCKIL976KquxyIMIW0QNddSIkWGStuYR9Whzujxtp2JeZJe296YmF0EH24hJQc9r9WHlA9Ke6XPZrvaOry6mHllLWFx4WjnZBSW8gdp19Llf,scmqyWA4al2e5Jybrr9FCV6F7ac4VknVjthqwDpIRf2spMf5ff95dWmtKKkBeCAneWcE8WJrIMGOUIsuSlJ43k8AGs4NZsPfXPMV422DS8LVpRXa2Fy647R2vK1CgluP5JhGCq4GIWDE7RDkSgFLYnHi5CATF3tmv66QBJ1XrTS3Kf3Zqh6O1MgALZbtojqBbcd2SWhiIzZwoFY3poeRBPV6NghRy3M6gmUyWCImgwFquqDOVDTSXWu87ilTBRkG,kUHDWp4wN0Z7Yc97dYSZ6RtjMtGLQ4Pmmdlxg0uGIO14S5QHJFECL7dP7xyBVPwu9s7kWJcqsvk5Q0losvMBkvtfEjHB9C0lKLtw54TXpku2GfOxrnB7vijr7Uzjp6LYJYzxmmiYShSpzVveIcFwIdMsRZRtY3sLzprPCi2v0PMduol8LwOy4wdVB56Sbgf7A1h6rEtPICQjm3KKKw2Iy89EYKX3VLwcGJ104VYGhx0fFCC1Ol2BR8IxcLrrP441,9fGjBTcOB6kA361q3D4qbF5kRXIS2Y7YA7U1vNIh66Hwv9rXPENL56UQ8ljZ6RjzTqPUoVb1NQxSQycdfMnaycsrSxxp2UbLdeDZ07jUABVQPZbthuyVlI6DBwKCblTDlUvl1tztc4EddICLKZb46C8ghtsh2Y3zPcgEBPA87Jr7mTkPVzUR8920Hzif8gENdqabCQS3pByn7uIW0qpCxg4YPWy92CUnHlKh7wWrI6yzXEGHmolZkEJcSBbzqQF,9rBx7t1Gc59TZINVc5kHC7T7tsjaBXqqxvb3wCUg0oievlhXXWkfuubfhkjmlzMzDtOQIiDKZBsPUlF8nM8ANepwWaguQpaX0v8ANo7gPxyStPZ5uovkFygpwlL32R8Nqj3FJbDpeNxGEiMyWmYTLdRi4YRedQdu8ptfGkvsgOt82rpOfmBVYPC1nvwMokXVcFxtt6XD81vPbB2UkIPyVfxn1xsSxqRCTlTHZWIIfblsAC32ZI3xBfCyi2z1YCNR,mtUZsmFelWZbjrgbcykKHGgWLjtSmgcGUWVLsZolaTV2QDxeCFRP8YIyQadWAkaS7fstOxJIaGPLG6NP6BLDcO87TRMTeyGK4uE2WHHGU9np4wIiUysfo1Tibkx8wAWZPedZ3feiq7SDLEdOhoLddU5fjpK8H4UV3z0R1l2kFbEhCpjGyBNW6lyNWPOSBtA2N40lSfuUdztR93H7n93C0NYrW25dWWrZV0S8aJG95aq2k4uYzZReChXNk602J9pr,BcsEs8cbkSSEhFUdqh6IyVau7SzU0IlYJLEjMkpouWWkQPHQFcZzku7WnFJ82nxepRlH1l2JKU7rwdHdlwLfwbvRn1Zief0mPyJ51piSBt0unvOmiKLUahy9Wu1EEqUnI0JxkY24i23OJZKH93ssRT0U4JC3eK5n2fzxVyXDmXkhIbQN6jyDOGX814PF164jdpge3nXkIe5YAcGwXbODBcHAHcEVllJi5rGHHMnj2jUvSpcX9TrB1EvN10vPcR2s,dZFgdIDlrddQrljoChA4OCd92NUMXcdKLIjsAi84vkuUuP1tsyEet5slCL0x8v0UvoG36WaI1RCkHcCPGhqEH6t5slgwYUeZHCzBUDkijyxPgyKyBVLKRBRyCAf5bdxGvDfR9uMZ1hlXd9GQuWaQadTeX6oz3HNp0LyYYFIeGAEAC4Q3DhiveFQTSFPDdZHtrwOkUO9ETVevp3uw90Q4DQm0wby22X0DdXEkTGdJ4gA2rO5HTw5mVpZvwba3JnnU,u3GxZbiZp40ZX9O0rpgdnvlg2713ZyIhc1NQSt5SXJbrxjYKU9Wbe10WVDv4ZDtRohLbWNipgNZ8DAS7xobnxDjzm6336WaJnxUAJGwM8ZF2cokNvFZfw0T9F1LbsSXEHI5MJMpxrgOxyn8u1FRmLa8WFGtkMehAaP8gCJbVdqUsJea01oAVIaNIWsiYERFug6CTxaprtcQQ50jk5gHkENqHaebVIulCCi7gT9DWqWDw65iikqJxUNyjWsAa1ASVnzPYrr36Daxtg5OvwUuOAn8Zn6WMyxGmYyw2AXYZFy19OX6ztNkFUEcOGFMkUNHd6a0N91xHrK4JUJFUMD1Gz6CFRywf8GgMZUdfFCwQUSFsQ1HQdpxA5AJWUyi3WpR3O9ESnCuBhHXKRUxdK8bD1ZkmcYIvwXQEn4nyq6IZNjDNzuHFVArNeEsPKwYZUOM0TOiRlp5JHYhrX6aLmIJzLs8pDzzdqhpBx7wo3KiR0PWj9xowkTf4QAQ89UIfgG5T,TrLRAf3Xlp2RQKiQBVMla0CyZUMZl6jQjaqlVIjAZAOIurkZ4Y443P10cifOyp0tHg3uRdZPbL0HFOmakp6qyCDgTmIciV6z7wfdTI0zf6FdWLJTfC0T2cKwjkzBzdOfu9CwZ1V2Xl7mESKsUB7Upcg5ZI3NlDIhKC3Q7bd75fn1Q5DNAp7XVc9s0cBy2xkoSfLGHykQwmcssJYCTMthbgeTNRkmUZN39sISYMqv053pysbHTpGrwixmKnSWBY7C,Au7OG4j9WOkJcPm9uS06RXsFm35S3TY4vIzZ0zKN2w9TsSgIoyGwE4OndjkdMiEJwpN1IUkwacItdaejVfbVQvgG89tmeFTxI2QFlP1rlakAEZQ6u7I3HfYaFo92r1LGmASl6K5p44rADSQx52oReDw0O0NLqUPR8DzzI5uykBgCGsHSuUarYudv5BemSIVAZDFEB1gcjjXA3BttIx8X4pw5B3Z6Nzjg1IWzx9WbvdIV6F0wgi9byI8wBDfXAtCY,3XZQ0KgJElORTjZePhrcmjJTngF8nzPqQIBsQPeRNXNtGghxlaIz9ogH3PtTdgrIQ4gIvUKrce0ftdsMiB0mtPfF6XI0fcAhRFCzuhGPuiJljtew82o3oBC3lGeBWpHz8SVJUflbRNj71pgcjZG6u7UF5eMiWLtxdrjVLQ8Zm3gEHo07Ipa0wSmV2GaTb82ONr2pxOvD2eS0HlMt4wR97b0AunUg6EhVAvzIGI3L4CZyyYKCpN9NcY5arsX0n9mw,mlgIFp0FNfutD3InGFv5CkIlcni24gh7NCJ2mZmCIzTID5Gg9daQbuLVKYVp68UpbhfajA4Fl2r6uvXx22E46gPQJ2tVD2NoMZBZlvj4EDwy9ZttoujHe3O2qwApvobNlrMOnig0ZuRCmN5w9VjOjvMkSOagw5fH1dqowmGzUL2mVNg8M2BhGkQu5EqcelGlhKGmTt8SSQuvZy92dCUPsGwmOz4uMuY0R7FPIQ6lg2zDsb2y1XKgIfZUMQ9QKDwM,hDNebDL0cegzxBm21GYLWmYeB8WF2pS3PjGPn2Z4jrcPKsLk0F6g599hdlwLfK58oh2uJmbPaIy70r12dCXV02k6HDbAbwPuMckefLbSNDveZoT96JGC0j6TCJkfXdsGgzIfsREctygfk1Y1xLabvadtVq4B8hhed3sz1yO2nwjeA4ZuUdaLwhzjElwtKxtw1Eb4ah4Irydp9EKacvMUOZUSGhj0fPZsvH6E4ttTwBX3Ti8MFrRosRBUJkCKEWYU,cFEEotEcDQEj84lLFlDdfEbYvZ7f1QP17zPWLIDNJ1j2NjTf8sd886ki9wLPuq3XOSjZXwi64axbQp5ibCFowQ5wAWnJXE78i5Lo8VaHLVm7MvR5pDF7z9YhfQSmgyEpYBFrYnlHXTUlU3mDiowJImTTwTjDdrzQ1ZLMifv6EscBBWsuXM6mZb3xHyoLdrVE3GkcCGGB7v2xVO9OWivAbe7q2gSbTpUGbn0bqgCvgYCzJshGAuPyvLsQcAW5qNNp,Wb8HwsJ9MssaKUlhAaTItf53op6SpCv9w09tSYdJNGRpLPfVCFeiylayO7VCUyiIEaCMwE1yC2o3erjL'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49486480-D84F-4A41-91D2-46864F6A7584
[ThaliCore] Advertiser: session connected Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:49486480-D84F-4A41-91D2-46864F6A7584 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 5, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 5, 6, 7, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (10909 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6, 7, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [5, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.did,SocketDisconnectHandler disconnecting:false
,2017-07-20 20:21:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:7 [5, 8, 9]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:8 [5, 9]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [5]
ok 96 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:49486480-D84F-4A41-91D2-46864F6A7584
,[ThaliCore] Session.session(_:peer:didChange:) peer:49486480-D84F-4A41-91D2-46864F6A7584 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49486480-D84F-4A41-91D2-46864F6A7584
,[ThaliCore] Session.startOutputStream(with:) peer:49486480-D84F-4A41-91D2-46864F6A7584
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [5, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49486480-D84F-4A41-91D2-46864F6A7584
[ThaliCore] Session.startOutputStream(with:) peer:49486480-D84F-4A41-91D2-46864F6A7584
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [5, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49486480-D84F-4A41-91D2-46864F6A7584
[ThaliCore] Session.startOutputStream(with:) peer:49486480-D84F-4A41-91D2-46864F6A7584
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [5, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (5546 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server sends data back to client (163,84 bytes):'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (4238 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received (3315 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server received all data: 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[Thal,iCore] VirtualSocket.deinit vsID:10 [5, 11, 12]
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'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server sends data b,ack to client (16384 bytes):'
2017-07-20 20:21:42 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.handleEventOnInputStream endEnc,ountered vsID:11
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [5, 12]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client dis,connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 20:21:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E56D8C9C-324B-480C-8DDC-9842424945C0
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20,:,21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:17C71F8D-4817-4678-B647-BED88DB07F70
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54508
[ThaliCore] Session.disconnect() peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:17C71F8D-4817-4678-B647-BED88DB07F70:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:21:42 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49486480-D84F-4A41-91D2-46864F6A7584 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:49486480-D84F-4A41-91D2-46864F6A7584
[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:21:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-20 20:21:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EF679B5-3D76-4807-9D2F-A1180B430C00 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E56D8C9C-324B-480C-8DDC-9842424945C0", generation: 0)
,[ThaliCore] Session.deinit peer:49486480-D84F-4A41-91D2-46864F6A7584
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:749D76DB-9759-4DF1-9711-8D08EA81A735
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D38DC5DF-BF6F-48F7-9DC9-8BEA126B7F40
[ThaliCore] Browser.startListening
,2017-07-20 20:21:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:21:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:21:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","generation":0}'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9571CE61-1016-4A87-8C94-F0E5DAB9C517 (syncValue: EwunALCNlhfhoh4j9VTlNTMUajNuNIii)'
,2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
2017-07-20 20:21:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C94593B-EFAB-4A2A-BBD8-57221E91DD91","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:44 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", g,eneration: 0)
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","generation":0}'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:21:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:749D76DB-9759-4DF1-9711-8D08EA81A735:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "749D76DB-9759-4DF1-9711-8D08EA81A735", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,71CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,71CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,71CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,71CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9571CE61,-1016-4A87-8C94-F0E5DAB9C517 error: max retries exceeded
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EwunALCNlhfhoh4j9VTlNTMUajNuNIii","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EwunALCNlhfhoh4j9VTlNTMUajNuNIii', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9571CE61-1016-4A87-8C94-F0E5DAB9C517","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:21:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:21:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C94593B-EFAB-4A2A-BBD8-57221E91DD91 (syncValue: QGCgKng,ZCeWtnIlqOmFDnhRzzDTciAZE)'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C94593B-EFAB,-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:21:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9571CE61-1016-4A87-8C94-F0E5DAB9C517:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9571CE61-1016-4A87-8C94-F0E5DAB9C517", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54532
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QGCgKngZCeWtnIlqOmFDnhRzzDTciAZE",,"error":null,"portNumber":54532}'
2017-07-20 20:21:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QGCgKngZCeWtnIlqOmFDnhRzzDTciAZE', error: 'null', listeningPort: '54532''
,Connecting to the localhost:54532
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [5, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:54532
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 20:21:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [5]
,# teardown
,2017-07-20 20:21:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:21:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:749D76DB-9759-4DF1-9711-8D08EA81A735
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54532
[ThaliCore] Session.disconnect,() peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:21:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:21:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D0A4B69D-C26E-481F-B495-6814F733A0E6
,2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F838878B-37A2-485E-B7FD-411FC46,0CF7F
[ThaliCore] Browser.startListening
2017-07-20 20:22:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:00 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:22:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","generation":0}'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1 (syncValue: LkM4sv2fHhOcwXpCiFbSXUMBOU0b499J)'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C94593B-EFAB-4A2A-BBD8-57221E91DD91","generation":0}'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4C94593B-EFAB-4A2A-BBD8-57221E91DD91:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4C94593B-EFAB-4A2A-BBD8-57221E91DD91", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:D0A4B69D-C26E-481F-B495-6814F733A0E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
2017-07-20 20:22:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
2017-07-20 20:22:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:22:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,76FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD
[ThaliCore] Advertiser: session connected Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD
[ThaliCore] Session.startOutputStream(with:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [5, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,76FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:22:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017,-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (15330 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (32850 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 20:22:07 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 20:22:08 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:89,76FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8976FF76,-77A8-4837-BB2A-DE6ED7BDD9E1 error: max retries exceeded
2017-07-20 20:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LkM4sv2fHhOcwXpCiFbSXUMBOU0b499J","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:22:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LkM4sv2fHhOcwXpCiFbSXUMBOU0b499J', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:22:11 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:22:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:22:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 988FB937-F1B1-480E-BDE3-7861620E8B1B (syncValue: tLjYWdX,fsGPm1cMUoVkb5BtNjfgqIEdk)'
2017-07-20 20:22:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:988FB937-F1B1,-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:22:11 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:22:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8976FF76-77A8-4837-BB2A-DE6ED7BDD9E1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
[ThaliCore] Advertiser: session connected Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
[ThaliCore] Session.startOutputStream(with:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [5, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54550
,2017-07-20 20:22:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tLjYWdXfsGPm1cMUoVkb5BtNjfgqIEdk","error":null,"portNumber":54550}'
,2017-07-20 20:22:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tLjYWdXfsGPm1cMUoVkb5BtNjfgqIEdk', error: 'null', listeningPort: '54550''
,Connecting to the localhost:54550
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
,Connected to the localhost:54550
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [5, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [5, 15]
,# teardown
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:15 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:18 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:20 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:20 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:20 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:22 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server received all data: 9kJRFLGuHC1dMr1F7bky6FefWNEGM3BR9Uu5H8QGnCybsLomNsrSxf9S4BPe9Vma4nuTx7459kdc0UDQRzPmBVXgm7NrUfqjWSMdvF4DIQragYgaPHTUBrXKa9UffvaOjfdpaRnoQpudDQbmKQzzOaQKQfJ8yaUTgdtuhzP5giQiZ0DnEi,Rduz1k3ApKuD9eC9DIB0IgOB5s1Cg2IsO2AH7T5qtwCsrd2zAdJhrSbyWrRRnnkWMTBcZVAcw2BSsEMCIXf0G0EvnYwo7kdZcfJW6WyPnQcaRtqg7TgxheNDlVPvsDaSSbzSAfA1wkArd8MrPSksk7I4gOcrjb3yCaLuZQNAQibzilkgKyvakxgzR2qEDkCF8iokHcokFUdp8Lf89k9V4AshtzjtE6ibbcsI1nnYXHpEwe88F2sKAhI3JgjQln6h,UEv8y29FkPuEk2vzrQoOCDTCYZkUmgqm0pCJzHGSrsN8lDOaQiH1oWGMPRvF3i52RB1DtNaarn7vVtSuY313xWb81fijR2AwSIfZjaBCL1d5du4jUF8w3cOna4DY7dGIOFRbpAeOmVm80qR52t1WPyZmcK4kLaD7BqaFiVMBX6ikaWkjgsUUn7kAMUOYEpg3xXfyQiwQ4rmV24z2Ih97n2cAUWMLefIXMCYw2nozwbIWJhBxN1qY1odNQ7mhS0wP,QFFE8InwabwztD2GYcQwqdU6Z4pwQYqryEfiZSnj1Co1KFczmyDTGbMVL3137BD0A7VmLXec6UWWFRZ2kVBEqHUwUKn8wudJli85LD0ZHrHlBloepqgzNUeTMInrSeJywv4cZviOHijajr1XNZnmADAYotoN5janNnz1BHauaV8iC6wtQnIHo9VBDhFTIXHuDkAe5cj5OwePVpniTqvjkxSGy6rBWKWClWmUryTUzp5zeA6ySs4j9lb7wybf6aB,LS9T3edmQYB1EIEXMoAkslafiWEs7UyIaMhXeBa40pFmVdm471uhMVGxqjG1fah8A1BUTl3WBxVsABUy4lJ1Xg2HhDIc8ZlKnXdCZV5dyubLHwdHm4zwnTWYsuCs2Q8hQfxW0lIZwpWJxGhxZoqXfqrc4rE2ccyU3I3CKndZQhYZakU9t44hW2gHgYyQE4atRns0J5sNdVH3PNT6B6QVB6lTBwZP3HSqSYGefELve2i5qbvhlE5ElgP56yNxdpyY,bN8uzTX34q0w3QYqSEEAqP2OsVotgdyfbk6Uk1pU7NHYp8JbFmXQkN0R8gvpTzZVxIWLNvn03Vmzlv829i0KzinsPagyp13hCcXbh8xOSuPTVKpharNpHZnFRRNGd7jV7DfFQLx4NI5d5AZrIDoWmGpLS9oYTmkeYcQvrLnLMB4CioL9UQXXJyqiV978GJpMjIpOQSIYufcQwG5W3FAnRf46EkzRTdZR81zTymXOPp94A9gijJRQL6ApHb8ZCCkz,uJIsmKrJ21EJP4gjeGeysXlOdSgVSzq2rqyToKPBCkGAwMJOE3GBzXzI98KM4y0kRx9iFCUlHW9V8qDHd6WYLC4GM6IDAVYcefgIXWE396yWi8DGdn9zSu4LzgXenPelS1zUdFJcUHP4wyNOJ69EUCm3tda0oAQ7HZuWpbsrJp7t1AKW3rtnXr8Ny9xOHRgCOGL3wqcqhStDbnua2VZcRwokrxsUzZX1zRVp2ZHfsNHnRPgWnqevNkeYwAtHHzBS,ExE7tPIcWDTpoKlq6ZgrDKV3C5qpFTJlhKBZOA9t5UVH9txmtGv51Mi5yKuNwAHCEbdfhX7C7IoDySKsx27spnI7kRQGgGHX3gcKIobpDSSrW3AHhLMX4M6zQ4ml8gaU9xnC9SURI5DMQI9I1dcLdYCaqhQ8uZ4NzYExoArl7NR3pVvWSw5cFDPWug9kQj8WCJzv5ygtXkcNxz5HUkBSx84o9vZ2EhrUHVQVV4YBTWvV6bRaWgVOlaqIyD4zoMC,R,JxT2p9Waqlvb5LvvLayglSyen9wc9MdPYsr5Uhfu5qzkwFvxQiNE7tYZ7SVUW6mWj2y4N3QdKRSOavUVSJhuNtTGLPq51mMfmSQ38WTe2Ys8SYJGomnOpe6aN6lfXPgiYV6wSC0S9ogtauHIJq969T07ingrvrvuC5nz0b0zWZp2SVv4KlVuCfIDQ6MtjrcegxOP7ryDRL2oybjso8GFBtefqaGudXWtuKQYf8NSlUjMd7YhtcjXhJGXlaw1GI05,P1FJMJtVngVYhPKcMEcARLZy0u7XLHVhjUYkD6H5eQprmObgPntrcjFYual5n3hY5fY8McXC5Pn9ayl7GyJCpJYzulfzoT9kEFoaqnMczzAVYz9WBdKfAtyr2OMaS1o6MluQqIAx9iLJvbAB7b35hOi9WkTfPFuSuiGq6q2qXETHzuppY0O8l8IvnJ1rbmDEPJJx2hODZInIe9yhreO9KwqQRUpD5O6DJqKC0RWldQqxkEngopOK5hv6COLr8Pks,3uEzY8sHNEfq1V0Ppu5KGCfv2mmqDIMkxdxIqXjNGpDkVnbmpzXyJrnDb3XnyzlhZoM2upzXzSarmY5eVk6VbQNKkv5ysrLJRncCb4EJvwmvY2xppj7cDZOLsyMKI2UeywDHuJUkjsIhtlZjPguwpox2WqELLKcYjxvOwOo3K1xjCShXZ3fdlMtADCtJS82Gb5JLTxXABARPCmt7VTKuZFnYMftGQwOPkkRingNnz7vYk66EmMjPr4r4YUvJigp6,uilfZmlboyD1jGdm7rC3pTfZIsc7b6Nf3dSU6Gw3fjuCRY99ZOIWP8ILgsBprjZZ4b6LAQrKn1vuQu0WwPiOHf5ay55rgL8Sw67Bn2lEZtbqG7ItEz0GTFAtjWqJ4RPz21a6q5mpZMrzfeLhX8VhfEk05GgfVVdvhgyGhiBND9EYgcrQdiax2d7ppBh8BUlwEO0SicOC5F81dVxmhopJF7707jUzcVkhQbcx3FAa2d7tBXZLxZWdukqoBrzNGTl,g,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,4,lQGyk7YB619dZNFQq2KDQrdMzfJYaFzxr5dUQelLdIfJQZCBxWoZPfc0SFk6HUhNRYqn8AxUOFTOnY70eeprs6V7q0dStTv0KeUCbd6220cWBhYf0ZtKe9ALHf0VbQRE34WFh5i8OqHh6vc5EsBsm17TzBIGgyre83u8diapPjLNzs0aR1xnl9TIGnW7AclTJrRbrh4arSkDjABeuoHXc0lHCxOxgAs4KLjzrMrfFfvBiMHvhYtfF9qWmeXMXbfi,Ee0xBmSYxtvBKBFT8fdPkxvFaqBzuRSUI9LCO1TpMxES8EUQaoWRl58SKGscmQsOy6Hr0Qf5nyYChfDnMsndCjEhFoVFyn7K4r7LBPPgCRy2yzWsVeveAv8OXKDFbikkjaMrLuLtXiuOeRoNJqGcv6RGcNT8L3DWCZUKU4nYkKibCdN8ae1mmbDxYYjaY9Xmi1fsByLqCHbYPkrPeUQESFcweQwDiZ1XPZAYxjZSKtgUERsTsYLT88n8PuX4l2uM,u6FbjazOYEqY4Gdg7w4S5zqLvMDuacXDGjj7juWOxS6vqBCki6rcIM2NuoKrkbohZ8Lqm8l8uGBGLCwJVOK1MEd5FXs1NCsAwkPJfnsTgjAB0dPFqgdg20ULjj0eXsuEAwFHFIVfgDZstbEZp4zzXduu1CcqI0PQBnXEZzftQUhJxNjMcZ6gVXN0HJK60MqdY5Xw8aSVvPEmEJ207fPdnCxnttYUDo6Evb5tgunGNWjsT4lRypqcLHwWKpe8Dkxy,nMnZTGjZXbWLQSRLwfVzGDLTevdbl1nut2anx0lHFYSAGcLHRKMaZgCINyBsl39SvJKHxrmFYJlDK4G5H8tymkEujFLWBZG8OLNta433tLqtyqD1a8Of8hf7NiD6mKjAaNodCdIDNbBaDgCOajbwyLNanoYyeV9hsGRxLWxjzbsx4WkwlcZMMmwdZAIWriOThs1XiIvQxLFAM3cyLYbKQ0Z8AZ0ZWlBIt4vRKT6Sdeo1mP8K1gdqQL8Zg6ocoTB,L,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'
2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 20:22:23 - DEBUG testThaliMobileNative: 'Server data flushed,'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
,2017-07-20 20:22:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:D0A4B69D-C26E-481F-B495-6814F733A0E6
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:,22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:988FB937-F1B1-480E-BDE3-7861620E8B1B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54550
[ThaliCore] Session.disconnect() p,eer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6F9504A5-D732-402E-8DB8-9A821A7D68DD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D0A4B69D-C26E-481F-B495-6814F733A0E6", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:A4F7EA10-A9A0-4F2A-BEAB-989981AB10BE
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2BF63654-1FAF-4697-A22E-B42E35C769C2
[ThaliCore] Browser.startListening
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9B6B5F25-9D48-43DF-94FB-5D4582DB9,1,55
2017-07-20 20:22:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:24 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:085DE6E9-1621-4798-93C4-92CEA205E383:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "085DE6E9-1621-4798-93C4-92CEA205E383", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}]'
2017-07-20 20:22:25 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"085DE6E9-1621-4798-93C4-92CEA205E383","generation":0}'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","generation":0}]'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","generation":0}'
,2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B6B5F25-9D48-43DF-94FB-5D4582DB9155:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B6B5F25-9D48-43DF-94FB-5D4582DB9155", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","generation":0}]'
2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","generation":0}'
2017-07-20 20:22:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9B6B5F25-9D48-43DF-94FB-5,D4582DB9155
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:29 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-20 20:22:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7826BDDD-E4DA-42AA-912C-6A47605A6B0C
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3636F35C-2603-468B-89F0-AEB49E9A8A45", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:3636F35C-2603-468B-89F0-AEB49E9A8A45
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3636F35C-2603-468B-89F0-AEB49E9A8A45
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-20 20:22:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-20 20:22:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 20:22:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 20:22:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:32 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 20:22:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:22:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:22:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:98dd2ef3-d3dd-46f4-8e94-377b71ec1d0b error: startListeningNotActive
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"NrPJobCBQ7dfMvtqsdyeK7bhHWO06wwH","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98dd2ef3-d3dd-46f4-8e94-377b71ec1d0b","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:34 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98dd2ef3-d3dd-46f4-8e94-3,7,7b71ec1d0b","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:925C3C8C-EEA2-41A5-827D-4DF480E9D9B0
[ThaliCore] Browser.startListening
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper:, 'multiConnectResolved: {"syncValue":"zlOmY1zZgvUe3GeWnOdjqS4g5oZwkdvg","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null,
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-20 20:22:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:35 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7E38F37-EDE3-441E-923C-FA1D415DEADF
[ThaliCore] Browser.startListening
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:29982467-4f65-4035-84b8-88bee19c0782
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2A5BDDF1-7B91-494B-BD51-A71449C556C9
2017-07-20 2,0:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6FAF675-B646-4914-A7AB-DD89C6CAB49F
[Tha,l,iCore] Browser.startListening
2017-07-20 20:22:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:22:38 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B,1B","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 988FB937-F1B1-480E-BDE3-7861620E8B1B, (syncValue: kWhV9NDDAWGdBlUliofDa1fV3FMfh3gE)'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BB0751A3-27D6-4D76-8838-BBBBB43AF0C5","generation":0}'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!',
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","generation":0}'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","generation":0}'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:22:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A5BDDF1-7B91-494B-BD51-A71449C556C9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB0751A3-27D6-4D76-8838-BBBBB43AF0C5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB0751A3-27D6-4D76-8838-BBBBB43AF0C5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:988FB937,-F1B1-480E-BDE3-7861620E8B1B error: max retries exceeded
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kWhV9NDDAWGdBlUliofDa1fV3FMfh3gE","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kWhV9NDDAWGdBlUliofDa1fV3FMfh3gE', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:22:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:22:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEB23978-DEDA-4875-A80E-C75021896629 (syncValue: SnuRmKj,g0JpcAGhepyelt7xYkwCreYHX)'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA,-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:22:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4CE93373-4EA4-471E-9989-210CAC263251
[ThaliCore] Advertiser: session connected Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93373-4EA4-471E-9989-210CAC263251 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4CE93373-4EA4-471E-9989-210CAC263251
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54565
2017-07-20 20:22:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SnuRmKjg0JpcAGhepyelt7xYkwCreYHX",,"error":null,"portNumber":54565}'
2017-07-20 20:22:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SnuRmKjg0JpcAGhepyelt7xYkwCreYHX', error: 'null', listeningPort: '54565''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,ok 143 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) found active relay
2017-07-20 20:22:52 - DEBUG thaliMobileNativeWrapper: 'multiConn,ectResolved: {"syncValue":"qUA79YLA6W8dkdVBKl6BXdK68wO57D0J","error":null,"portNumber":54565}'
ok 144 No error
ok 145 Ports equal
ok 146 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23,978-DEDA-4875-A80E-C75021896629", generation: 0) found active relay
2017-07-20 20:22:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HkYwBulbgoYyHsS7ySpPr8uIIWjjIQgI","error":null,"portNumber":54565}'
ok 147 No error
ok 148 Por,ts equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [5, 15, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93373-4EA4-471E-9989-210CAC263251 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4CE93373-4EA4-471E-9989-210CAC263251
[ThaliCore] Session.startOutputStream(with:) peer:4CE93373-4EA4-471E-9989-210CAC263251
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [5, 15, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:22:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:22:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:22:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:2A5BDDF1-7B91-494B-BD51-A71449C556C9
2017-07-20 20:22:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20,:,22:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Advertise,rRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserManager.disconnect peer:FEB23978-DEDA-4875-A80E-C75021896629
[ThaliCore] BrowserRelay.closeRelay() state:connected
[Tha,liCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54565
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisco,n,nect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:18 [5, 15, 17]
[ThaliCore] Session.disconnect() peer:FEB23978-DEDA-4875-A80E,-C75021896629:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:17 [5, 15]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered, to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93373-4EA4-471E-9989-210CAC263251 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2A5BDDF1-7B91-494B-BD51-A71449C556C9", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4CE93373-4EA4-471E-9989-210CAC263251
,[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,[ThaliCore] Session.deinit peer:4CE93373-4EA4-471E-9989-210CAC263251
,# teardown
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-20 20:22:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-20 20:22:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-20 20:22:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:22:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:22:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-20 20:22:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:22:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:22:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 54569'
ok 149 Should throw
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'listening 54571'
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-20 20:22:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:22:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 54574'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 54578'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'listening 54583'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:22:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 54587'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'listening 54591'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:00 - DEBUG createNativeListener: 'Native Server - close'
2017-07-20 20:23:00, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:00 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 54595'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - close'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 170 native server is nulled out
ok 171 native server should be cl,osed
ok 172 incoming has been removed
ok 173 Incoming should be done
ok 174 The mux object should be closed
ok 175 The mux stream should be closed
2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection ,<-> Mux - 0 - close'
,# teardown
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'listening 54599'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-20 20:23:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 20:23:01 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 54651'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'listening 54655'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-20 20:23:02 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:02 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 54658'
ok 196 port must be in range
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 20:23:03 - DEBUG createNativeListener: 'listening 54659'
ok 197 second start should return same port
,# teardown
,2017-07-20 20:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 20:23:04 - DEBUG createNativeListener: 'listening 54661'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 20:23:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-20 20:23:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-20 20:23:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 54663
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BD9B4A1C-33E8-444D-AF81-B5888BAC5468
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1C9D3398-C78B-4A10-9D03-B59AD32,B28CA
[ThaliCore] Browser.startListening
2017-07-20 20:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:23:05 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:05 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
2017-07-20 20:23:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEB23978-DEDA-4875-A80E-C75021896629:0
2017-07-20 20:23:05 - DEBUG thaliMob,ileNativeTestUtils: 'Issuing multiConnect for 988FB937-F1B1-480E-BDE3-7861620E8B1B (syncValue: fZc4L3b91V7sORhfscmFJouDkBXZOug9)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
2017-07-2,0 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98,8FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","generation":0}'
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","generation":0}'
2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9B4A1C-33E8-444D-AF81-B5888BAC5468:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
2017-07-20 20:23:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","generation":0}'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
2017-07-20 20:23:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","generation":0}'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:06 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,88FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A
[ThaliCore] Advertiser: session connected Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A
,[ThaliCore] Session.session(_:peer:didChange:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:98,8FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "988FB937-F1B1-480E-BDE3-7861620E8B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:988FB937-F1B1-480E-BDE3-7861620E8B1B error: max retries exceeded
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fZc4L3b91V7sORhfscmFJouDkBXZOug9","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fZc4L3b91V7sORhfscmFJouDkBXZOug9', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"988FB937-F1B1-480E-BDE3-7861620E8B1B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0635C8F3-9DF4-4970-BF0F-2DCA782B004F (syncValue: cmpDYJG,O46QvtTPrT85Yzr5WiBVaRTgU)'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0635C8F3-9DF4,-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:988FB937-F1B1-480E-BDE3-7861620E8B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:06,35C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0635C8F3-9DF4-4970-BF0F-2DCA782B004F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cmpDYJGO46QvtTPrT85Yzr5WiBVaRTgU","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cmpDYJGO46QvtTPrT85Yzr5WiBVaRTgU', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0635C8F3-9DF4-4970-BF0F-2DCA782B004F","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEB23978-DEDA-4875-A80E-C75021896629 (syncValue: DeTuovXUlvLrL1OYLiebVhr9ROVwoQtF)'
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0635C8F3-9DF4-4970-BF0F-2DCA782B004F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,B23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,EB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
,[ThaliCore] Session.disconnect() peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
[ThaliCore] Advertiser: session connected Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FEB23978-DEDA-4875-A80E-C75021896629:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEB23978-DEDA-4875-A80E-C75021896629:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,B23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FEB23978,-DEDA-4875-A80E-C75021896629 error: max retries exceeded
2017-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DeTuovXUlvLrL1OYLiebVhr9ROVwoQtF","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DeTuovXUlvLrL1OYLiebVhr9ROVwoQtF', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FEB23978-DEDA-4875-A80E-C75021896629","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 20:23:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F256E69-5A96-411E-9BF5-88677F81218D (syncValue: HjrceGg,Bu5SS9iukHf3VLpgThFtiMr4O)'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F256E69-5A96,-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F256E69-5A96-411E-9BF5-88677F81218D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54687
2017-07-20 20:23:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HjrceGgBu5SS9iukHf3VLpgThFtiMr4O",,"error":null,"portNumber":54687}'
2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HjrceGgBu5SS9iukHf3VLpgThFtiMr4O', error: 'null', listeningPort: '54687''
,ok 210 should be equal
2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB (syncValue: IjvwmdpgboNY9EmfxyI9gDK6StCLF5QF)'
2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FEB23978-DEDA-4875-A80E-C75021896629:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FEB23978-DEDA-4875-A80E-C75021896629", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54691
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IjvwmdpgboNY9EmfxyI9gDK6StCLF5QF",,"error":null,"portNumber":54691}'
2017-07-20 20:23:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IjvwmdpgboNY9EmfxyI9gDK6StCLF5QF', error: 'null', listeningPort: '54691''
,ok 211 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BD9B4A1C-33E8-444D-AF81-B,5888BAC5468
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:3F256E69-5A96-411E-9BF5-88677F81218D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54687
[ThaliCore] Sessi,on.disconnect() peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
,[ThaliCore] Session.deinit peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54691
[ThaliCore] Session.disconnect() peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:23:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:23:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D0BA7B-3CAD-4F19-9B8B-5F9423EAB70A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BD9B4A1C-33E8-444D-AF81-B5888BAC5468", generation: 0)
,# setup
,[ThaliCore] Session.deinit peer:4322A2EA-9C83-4291-8F9E-C045DC789AA2
,# Multiple local http requests
,listening on 54693
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:23:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9A98DC0A-C695-4EE0-9277-E7A16E380EFA
[Tha,l,iCore] Browser.startListening
2017-07-20 20:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:23:37 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:23:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","generation":0}'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB (syncValue: agLV6E9jbMyS6YiPkVrvjyWxJZOHwaZ7)'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F256E69-5A96-411E-9BF5-88677F81218D","generation":0}'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F256E69-5A96-411E-9BF5-88677F81218D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F256E69-5A96-411E-9BF5-88677F81218D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"54EFAE80-90BC-47EB-A297-F97D6E577012","generation":0}'
2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 20:23:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,D4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:23:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"agLV6E9jbMyS6YiPkVrvjyWxJZOHwaZ7","error":"Peer is unavailable","portNumber":null}'
2017-07-20 20:23:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'agLV6E9jbMyS6YiPkVrvjyWxJZOHwaZ7', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:23:44 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:23:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 20:23:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 20:23:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 20:23:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 20:23:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 369058E2-8F68-45CB-BB58-78A0C9B96289 (syncValue: P839cWMvbRskqjUbquFXG3V,Cf8DG7T6w)'
2017-07-20 20:23:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C,9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:23:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AD4CB42A-D7B2-4896-9BED-4A25A1B0B2FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54707
2017-07-20 20:23:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P839cWMvbRskqjUbquFXG3VCf8DG7T6w",,"error":null,"portNumber":54707}'
2017-07-20 20:23:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P839cWMvbRskqjUbquFXG3VCf8DG7T6w', error: 'null', listeningPort: '54707''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-20 20:23:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 54EFAE80-90BC-47EB-A297-F97D6E577012 (syncValue: mIHh45FUu3dWGwZvYOohnDA3K6YavjEw)'
,2017-07-20 20:23:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "54EFAE80-90BC-47EB-A297-F97D6E577012", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54714
2017-07-20 20:23:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mIHh45FUu3dWGwZvYOohnDA3K6YavjEw",,"error":null,"portNumber":54714}'
2017-07-20 20:23:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mIHh45FUu3dWGwZvYOohnDA3K6YavjEw', error: 'null', listeningPort: '54714''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
[ThaliCore] Advertiser: session connected Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84
[ThaliCore] Advertiser: session connected Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84
,[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:42561EB6-F4DC-4C01-835D-B30B08258B84 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42561EB6-F4DC-4C01-835D-B30B08258B84
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C31016F-A39B-4BEE-9892-6C4A68B827D2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CA1C72E1-F0AA-4409-A8FA-03BA0D1D8B6E", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,20:24:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CA1C72E1-F0AA-4409-A8FA-0,3BA0D1D8B6E
2017-07-20 20:24:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:369058E2-8F68-45CB-BB58-78A0C9B96289
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54707
[ThaliCore] Session.disconnect() peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:42561EB6-F4DC-4C01-835D-B30B08258B84
[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:54EFAE80-90BC-47EB-A297-F97D6E577012
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54714
[ThaliCore] Session.disconnect() peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:54EFAE80-90BC-47EB-A297-F97D6E577012:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 20:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered ,to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:05 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'listening 54718'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:07 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 54719'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B5A06A2-7919-480A-90E8-516093656697
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
# teardown
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'listening 54720'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7181C031-63B6-42B0-B822-B7E5355C559B", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:7181C031-63B6-42B0-B822-B7E5355C559B
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:2,4:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7181C031-63B6-42B0-B822-B7E5355C559B", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:7181C031-63B6-42B0-B822-B7E5355C559B
2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,7-20 20:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7181C031-63B6-42B0-B822-B7E5355C559B
[ThaliCore] Advertiser.stopAdvertising() peerID:7181C031-63B6-42B0-B822-B7E5355C559B
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'listening 54723'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-20 20:24:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 54724'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC711F2E-3691-44E5-83FA-C2F7C928E732
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7DB7D33D-FA48-4703-8F80-A443213E08BF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,7DB7D33D-FA48-4703-8F80-A443213E08BF
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7DB7D33D-FA48-4703-8F80-A443213E08BF
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 54727'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C08E5BE6-106C-49B0-A2D5-E8D3AAF12304
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BC5BEED9-21F1-447D-977B-41428C7E81D0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BC5BEED9-21F1-447D-977B-41428C7E81D0
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BC5BEED9-21F1-447D-977B-41428C7E81D0
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 20:24:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:09 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-20 20:24:09 - DEBUG thaliMobileNativeWrapper: 'listening 54729'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6C706F7F-0BF8-4386-9FB4-73B36BA5A869
[ThaliCore] Browser.startListening
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0B1DAB09-F635-4CB7-AF78-18C68DC6EED7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0B1DAB09-F635-4CB7-AF78-18C68DC6EED7
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0B1DAB09-F635-4CB7-AF78-18C68DC6EED7
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:2,4:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 ,20:24:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifi,er":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0},'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-20 20:24:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 20:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-20 20:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 20:24:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-20 20:24:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:14 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 20:24:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 54732'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE713E84-E23F-44D5-998C-7D2FE58CCCFA
[ThaliCore] Browser.startListening
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 54733'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC97D3DD-EF7A-4AC9-9D0B-2A61A43C41F5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DC97D3DD-EF7A-4AC9-9D0B-2A61A43C41F5
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DC97D3DD-EF7A-4AC9-9D0B-2A61A43C41F5
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 54735'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'listening 54736'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19A6F823-2EC0-4E42-A812-F0BBD55BB1BA
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "53BADF4F-96FC-4937-A65B-FDD453B5A6EB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,53BADF4F-96FC-4937-A65B-FDD453B5A6EB
2017-07-20 20:24:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:15 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:15 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:534D867D-8D26-4A98-8194-F5DC97795695:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "534D867D-8D26-4A98-8194-F5DC97795695", generation: 0)
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","generation":0}]'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","generation":0}'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:53BADF4F-96FC-4937-A65B-FDD453B5A6EB
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-20 20:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-20 20:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-20 20:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'listening 54738'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8163C1B7-8E0B-445A-BE76-E11988518152
,[ThaliCore] Browser.startListening
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:603D95D4-183F-4EC9-B17D-817535F98047
,2017-07-20 20:24:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:24:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 369058E2-8F68-45CB-BB58-78A0C9B96289 (syncValue: IrcGSd2DhNCM2BjQsz7zNqirKDbcQOwP)'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}]'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:603D95D4-183F-4EC9-B17D-817535F98047:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE86867-1917-499E-88A8-9DE0439C821C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE86867-1917-499E-88A8-9DE0439C821C", generation: 0)
2017-07-20 20:24:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","generation":0}]'
2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","generation":0}'
,2017-07-20 20:24:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:20 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 20:24:20 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,9058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,69058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C504B930-A815-4606-B525-8D634ECAFF89
[ThaliCore] Advertiser: session connected Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C504B930-A815-4606-B525-8D634ECAFF89 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,9058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,69058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
[ThaliCore] Advertiser: session connected Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C504B930-A815-4606-B525-8D634ECAFF89
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
,[ThaliCore] Session.session(_:peer:didChange:) peer:C504B930-A815-4606-B525-8D634ECAFF89 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C504B930-A815-4606-B525-8D634ECAFF89
[ThaliCore] Session.startOutputStream(with:) peer:C504B930-A815-4606-B525-8D634ECAFF89
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [5, 15, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}]'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","generation":0}'
,2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:27 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,9058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,69058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "369058E2-8F68-45CB-BB58-78A0C9B96289", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IrcGSd2DhNCM2BjQsz7zNqirKDbcQOwP","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IrcGSd2DhNCM2BjQsz7zNqirKDbcQOwP', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:24:27 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"369058E2-8F68-45CB-BB58-78A0C9B96289","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:369058E2-8F68-45CB-BB58-78A0C9B96289
2017-07-20 20:24:27 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-20 20:24:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6 (syncValue: hCx08ZsaklnBlF0dubOkfrcxylfveZmt)'
2017-07-20 20:24:27 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E5,D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:369058E2-8F68-45CB-BB58-78A0C9B96289:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
[ThaliCore] Session.startOutputStream(with:) peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [5, 15, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54750
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hCx08ZsaklnBlF0dubOkfrcxylfveZmt","error":null,"portNumber":54750}'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hCx08ZsaklnBlF0dubOkfrcxylfveZmt', error: 'null', listeningPort: '54750''
,2017-07-20 20:24:30 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [5, 15, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:30 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:30 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:603D95D4-183F-4EC9-B17D-817535F98047
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 20:24:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:30 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDid,D,isconnect(_:withError:) client disconnected
[ThaliCore] BrowserManager.disconnect peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketError,Domain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54750
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening s,ocket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [5, 15, 20, 21]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] Session.disconnect() peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:21 [5, 15, 20]
[ThaliCore] TCPListener.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false,
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] Session.deinit peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] VirtualSocket.deinit vsID:20 [5, 15]
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:C504B930-A815-4606-B525-8D634ECAFF89 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "603D95D4-183F-4EC9-B17D-817535F98047", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
,[ThaliCore] Session.deinit peer:09D2BF65-9C60-4653-8990-CE41CD5662DA
[ThaliCore] AdvertiserRelay.deinit
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 20:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 20:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-20 20:24:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-20 20:24:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 20:24:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 20:24:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 20:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-20 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"534D867D-8D26-4A98-8194-F5DC97795695","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:24:32 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CBE86867-1917-499E-88A8-9DE0439C821C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'listening 54752'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 20:24:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 54753'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:105D8121-5428-4103-9D59-D4C0F8D1E10B
[ThaliCore] Browser.st,artListening
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:24:34 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:24:34 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:34 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'listening 54754'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A9A08D27-6039-473B-95B0-B840D2C5FA8F", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:A9A08D27-6039-473B-95B0-B840D2C5FA8F
2017-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A9A08D27-6039-473B-95B0-B840D2C5FA8F", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:A9A08D27-6039-473B-95B0-B840D2C5FA8F
20,17-07-20 20:24:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A9A08D27-6039-473B-95B0-B840D2C5FA8F
[ThaliCore] Advertiser.stopAdvertising() peerID:A9A08D27-6039-473B-95B0-B840D2C5FA8F
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 54757'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 20:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-20 20:24:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 20:24:35 - DEBUG thaliMobileNativeWrapper: 'listening 54758'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 20:24:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-20 20:24:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-20 20:24:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bf294b1-1e47-4fbd-b138-9a09e681578d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-20 20:24:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3bf294b1-1e47-4fbd-b138-9a09e681578d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3ab0974c-5333-4130-978c-d5db6b5fb90f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 354 peer should be ,available
ok 355 cache contains native peer
2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3ab0974c-5333-4130-978c-d5db6b5fb90f","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f0e4688-c727-4468-a570-86de572e6d8b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 peer should be a,vailable
ok 363 cache contains wifi peer
2017-07-20 20:24:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f0e4688-c727-4468-a570-86de572e6d8b","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f27b6f7-d187-4f2b-a553-db9646577d5b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4752c208-82eb-4942-9b01-b62b1b68e981","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 370 second peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f27b6f7-d187-4f2b-a553-db9646577d5b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4752c208-82eb-4942-9b01-b62b1b68e981","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b64095a4-a657-4342-9fd8-d5a64779b1f9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-20 20:24:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b64095a4-a657-4342-9fd8-d5a64779b1f9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-20 20:24:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
,ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-20 20:24:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc84365e-d887-4c2b-ab2f-9ba687a6d552","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fc84365e-d887-4c2b-ab2f-9ba687a6d552","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fc84365e-d887-4c2b-ab2f-9ba687a6d552","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 54759'
2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7adc5acf-fbff-4777-9895-20de0e1577ae","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7adc5acf-fbff-4777-9895-20de0e1577ae","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered corr,ect peer
ok 395 got correct generation
,# teardown
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7adc5acf-fbff-4777-9895-20de0e1577ae","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 20:24:39 - DEBUG thaliMobileNativeWrapper: 'listening 54760'
,2017-07-20 20:24:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"56a7f9de-31c6-418b-9660-bf4acd3e785a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered avai,lable peer
ok 400 peer is available
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"56a7f9de-31c6-418b-9660-bf4acd3e785a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2258d581-abb6-4da2-8d73-e003ab4092d1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2258d581-abb6-4da2-8d73-e003ab4092d1","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 54761'
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e9baaa0c-43aa-4130-b2cd-be3f002c23af","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d425e6aa-b97b-492f-9496-9e9c1734f510","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d425e6aa-b97b-492f-9496-9e9c1734f510","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d425e6aa-b97b-492f-9496-9e9c1734f510","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d425e6aa-b97b-492f-9496-9e9c1734f510","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e9baaa0c-43aa-4130-b2cd-be3f002c23af","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-20 20:24:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 20:24:40 - DEBUG thaliMobileNativeWrapper: 'listening 54762'
2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8698061-a4e5-4cab-974c-7d345f69f3c5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a55b05b-2b4d-4cf7-8d86-62e0ed5f66ad","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f8698061-a4e5-4cab-974c-7d345f69f3c5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-20 20:24:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a55b05b-2b4d-4cf7-8d86-62e0ed5f66ad","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 20:24:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:24:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b49c4923-6088-45b5-8574-5fd282c5825d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b49c4923-6088-45b5-8574-5fd282c5825d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b49c4923-6088-45b5-8574-5fd282c5825d","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b49c4923-6088-45b5-8574-5fd282c5825d","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-07-20 20:24:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b49c4923-6088-45b5-8574-5fd282c5825d","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-20 20:24:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-20 20:24:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-20 20:24:43 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-20 20:24:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-20 20:24:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 54763'
2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c358b251-a1b8-48a5-b27e-6c24b67c4254","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c358b251-a1b8-48a5-b27e-6c24b67c4254","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'listening 54764'
2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2208c5c1-c754-4d4d-815f-a3ba82a10d16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:2208c5c1-c754-4d4d-815f-a3ba82a10d16
ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 20:24:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2208c5c1-c754-4d4d-815f-a3ba82a10d16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
,ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-20 20:24:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-20 20:24:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-20 20:24:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'listening 54765'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:86564FC4-DA0E-4DC8-8B32-2CA488372D15
[ThaliCore] Browser.startListening
2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"add0d6e8-e161-4844-882a-f91b8e25512,9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
ok 504 Peer availabilities has one entry for our connection type
,2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0dd12f7d-4a22-4874-bd06-1e338f30e119","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"add0d6e8-e161-4844-882a-f91b8e255129","connectionType":"MPCF","peerAvai,lable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:24:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0dd12f7d-4a22-4874-bd06-1e338f30e119","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:24:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-20 20:24:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:24:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}]'
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}'
,2017-07-20 20:24:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'listening 54766'
2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"90833cb5-1327-4899-bfee-562c83b761e4","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"48ee0116-6b06-43cb-a85d-10ff3ac01622","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"90833cb5-1327-4899-bfee-562c83b761e4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 20:24:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"48ee0116-6b06-43cb-a85d-10ff3ac01622","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
,2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 20:24:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:24:47 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 20:24:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'listening 54767'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C2BF93C0-656C-4565-8E64-9D,866559AD79", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C2BF93C0-656C-4565-8E64-9D866559AD79
2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 522 error should be null
,ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:99EB9544-2E9A-42F8-B8E1-291264942B58
[ThaliCore] Browser.startListening
2017-07-20 20:24:48 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}]'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6 (syncValue: 0)'
,2017-07-20 20:24:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","generation":0}]'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","generation":0}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C2BF93C0-656C-4565-8E64-9D866559AD79:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","generation":0}]'
[ThaliCore] Session.init(session:identifier:co,nnected:notConnected:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] Advertiser: session connected Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadDat,a:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B231361-A704-4021-AD20-3523B68F9F1A state: notConnected -> connecting
2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","generation":0}'
,2017-07-20 20:24:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:24:49 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}]'
,2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","generation":0}'
,2017-07-20 20:24:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:24:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B231361-A704-4021-AD20-3523B68F9F1A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] Session.startOutputStream(with:) peer:8B231361-A704-4021-AD20-3523B68F9F1A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [5, 15, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
[ThaliCore] Advertiser: session connected Peer(uuid: "C2BF93C0-656C-4565-8E64-9D866559AD79", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:24:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,0 20:24:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:24:53 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 20:24:53 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67C489F9-6AF1-4BB0-8C69-0EC08B235189 (syncValue: 1)'
2017-07-20 20:24:53 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-20 20:24:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-,2,0 20:24:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67C489F9-6AF1-4BB0-8C69-0EC08B235189", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54776
2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":54776,}'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 640FCAA2-E8A9-419B-A56C-205453BA21D8 (syncValue,: 2)'
2017-07-20 20:24:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0) creating a new relay
[,ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67C489F9-6AF1-4BB0-8C69-0EC08B235189:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [5, 15, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
[ThaliCore] Session.startOutputStream(with:) peer:B9C655F6-DD41-4DF3-B3A8-8817961F8837
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [5, 15, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:24:56 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "640FCAA2-E8A9-419B-A56C-205453BA21D8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54781
2017-07-20 20:24:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":54781,}'
,[ThaliCore] BrowserManager.disconnect peer:E5D8D790-5AA9-450B-BB53-D6A9AC6FC7F6
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:640FCAA2-E8A9-419,B-A56C-205453BA21D8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:640FCAA2-E8A9-419B-A56C-205453BA21D8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [5, 15, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:24:59 - DEBUG testUtils: 'Got response data'
2017-07-20 20:24:59 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-20 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67C489F9-6AF1-4BB0-8C69-0EC08B235189","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:25:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"640FCAA2-E8A9-419B-A56C-205453BA21D8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C2BF93C0-656C-4565-8E64-9D866559AD79
,2017-07-20 20:25:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:25:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 20:25:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:25:00 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:25:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:25:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [5, 15, 22, 23, 25]
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:22 [5, 15, 23, 25]
,ok 527 error should be null
,ok 528 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [5, 15, 23]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [5, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket erro,r:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 20:25:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
,2017-07-20 20:25:01 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 20:25:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
,ok 547 agent's destroy should not be called again
,ok 548 agent is destroyed
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
ok 578 Size should be MAXSIZE+6
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
,ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
ok 595 good enqueue
,ok 596 Identity should match
,2017-07-20 20:25:07 - DEBUG testUtils: 'Got response data'
,2017-07-20 20:25:07 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-20 20:25:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 609 good enqueue
ok 610 queue is not empty
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
ok 615 already enqueued
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
ok 625 second NOOP kill
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
,2017-07-20 20:25:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 20:25:11 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 636 Got right error
ok 637 Start should not be called
ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-20 20:25:11 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-07-20 20:25:12 ,- DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-07-20 ,20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 651 Still looking for null
2017-07-20, 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneA,t,ATime: 'Replication action failed badly so we are going to retry'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 652 Yup, another null
ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
,ok 655 (unnamed assert)
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-20 20:25:12 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-07-20 20:25:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 20:25:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-20 20:25:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-20 20:25:14 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-07-20 20:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-20 20:25:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-20 20:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-20 20:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-07-20 20:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-20 20:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
ok 691 Start after killed
,# teardown
,2017-07-20 20:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-20 20:25:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-20 20:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 697 must return null after successful call
,# teardown
,2017-07-20 20:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 20:25:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-20 20:25:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-20 20:25:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 724 good beacon
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
ok 736 secrets match
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
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 20:25:37 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-20 20:25:38 - WARN thaliNotificationClient: 'peer is not available'
ok 746 notification peer dictionary does not contain any peers
2017-07-20 20:25:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 20:25:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-20 20:25:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-20 20:25:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-20 20:25:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-20 20:25:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
ok 758 portNumber must match
ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-20 20:25:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-20 20:25:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 20:25:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-20 20:25:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-20 20:25:45 - WARN thaliNotificationClient: 'peer is not available'
2017-07-20 20:25:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-20 20:25:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-20 20:25:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-20 20:25:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-20 20:25:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
,# teardown
,2017-07-20 20:25:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-20 20:25:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-20 20:25:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-20 20:25:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-20 20:25:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-20 20:25:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 20:25:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-20 20:25:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
# teardown
,2017-07-20 20:25:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 20:25:57 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-20 20:25:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-20 20:25:59 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 821 listener has been set
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
,2017-07-20 20:25:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 834 start called once
ok 835 One entry left
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
,2017-07-20 20:25:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-20 20:26:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:26:00 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-20 20:26:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-20 20:26:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-20 20:26:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 20:26:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-20 20:26:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-20 20:26:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-20 20:26:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-20 20:26:03 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-20 20:26:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-20 20:26:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-20 20:26:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-20 20:26:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 20:26:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-20 20:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 20:26:16 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 20:26:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-20 20:26:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 20:26:19 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-20 20:26:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 20:26:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-20 20:26:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-20 20:26:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 20:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'listening 54908'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42F9B46E-0345-4D14-84B1-6D2B7D21DCCE
[ThaliCore] Browser.startListening
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F90916C-93B2-4AEA-A154-B951CA01BF30
,2017-07-20 20:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 3)'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F90916C-93B2-4AEA-A154-B951CA01BF30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Advertiser: session connected Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54911
2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":54911}'
,2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 4)'
2017-07-20 20:26:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [5, 15, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Advertiser: session connected Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [5, 15]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outpu,tStream:) vsID:27 [5, 15, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,8 [5, 15, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [5, 15, 27]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [5, 15, 27, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 20:26:32 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> connecting
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [5, 15, 27, 29, 30]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [5, 15, 27, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [5, 15, 27, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [5, 15, 27, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [5, 15, 27, 29, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
,[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,38
[ThaliCore] VirtualSocket.deinit vsID:38 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:33 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54928
,2017-07-20 20:26:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":54928}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 41]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:34 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 42, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [5, 15, 27, 29, 30, 31, 32, 33, 34, 35, 37, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [5, 15, 29, 30, 31, 32, 33, 34, 35, 37, 42, 43, 44, 45, 46]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Cod,e=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserR,elay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [5, 15, 30, 31, 32, 33, 34, 35, 37, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client d,isconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [5, 15, 31, 32, 33, 34, 35, 37, 42, 43, 44, 45, 46]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [5, 15, 32, 33, 34, 35, 37, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.,socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [5, 15, 32, 34, 35, 37, 42, 43, 44, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [5, 15, 32, 34, 35, 42, 43, 44, 45, 46]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [5, 15, 34, 35, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [5, 15, 34, 35, 42, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [5, 15, 34, 35, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] BrowserRelay.didOpenVirtual,SocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [5, 15, 34, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [5, 15, 34, 42, 43, 44, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,0 [5, 15, 34, 42, 43, 44, 45, 46, 47, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [5, 15, 34, 42, 44, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [5, 15, 34, 42, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:47 [5, 15, 34, 42, 45, 46, 48, 49, 50]
,2017-07-20 20:26:35 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [5, 15, 34, 42, 45, 46, 48, 50]
,2017-07-20 20:26:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [5, 15, 34, 45, 46, 48, 50]
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [5, 15, 34, 46, 48, 50]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsI,D:46 [5, 15, 34, 48, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disc,onnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [5, 15, 34, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3F90916C-93B2-4AEA-A154-B951CA01BF30
2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddre,ssPort":null}'
2017-07-20 20:26:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":nu,ll}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:26:36 - INFO thaliMobile: 'Received sta,t,e ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:26:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,",advertisingActive":false}'
2017-07-20 20:26:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:26:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 867 passed
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:48 [5, 15, 34]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'listening 54940'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:03CE425A-6954-48CE-A2B8-645F09D668CE
[ThaliCore] Browser.startListening
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5E079B7C-5E99-4561-83E0-A4660711AA6F
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
2017-07-20 20:26:37 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E,6-9EE7-B3AAB0664285 (syncValue: 5)'
2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generat,i,on: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":54911}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 6)'
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,2017-07-20 20:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":54928}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [5, 15, 34, 51]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:37 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [5, 15, 34, 51, 52]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:52 [5, 15, 34, 51]
,2017-07-20 20:26:37 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,3 [5, 15, 34, 51, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [5, 15, 34, 51]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [5, 15, 34, 51, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [5, 15, 34, 51]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 7)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":54928}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [5, 15, 34, 51, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [5, 15, 34, 51]
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 8)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":54911}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [5, 15, 34, 51, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [5, 15, 34, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [5, 15, 34, 51, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [5, 15, 34, 51]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [5, 15, 34, 51, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [5, 15, 34, 51]
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 9)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":54911}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 10)'
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
,2017-07-20 20:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":54928}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [5, 15, 34, 51, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [5, 15, 34, 51, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
[ThaliCore] Session.startOutputStream(with:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [5, 15, 34, 51, 59, 60, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [5, 15, 34, 51, 59, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "C,onnection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream e,ndEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:59 [5, 15, 34, 51, 61]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.deinit vsID:61 [5, 15, 34, 51]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-20 20:26:38 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Session.startOutputStream(with:) peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [5, 15, 34, 51, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [5, 15, 34, 51]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] Advertiser: session connected Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EB94D05F-0832-4170-8059-233820381033 state: notConnected -> connecting
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 11)'
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) found active relay
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":54911}'
[,ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 12)'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) found active relay
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":54928}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [5, 15, 34, 51, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [5, 15, 34, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted soc,ket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:39 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5E079B7C-5E99-4561-83E0-A4660711AA6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","generation":0}]'
2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","generation":0}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}]'
2017-07-20 20:26:39 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 20:26:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:26:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 671A5B41-0FE3-43CA-96C3-FB13B9B80FEC (syncValue: 13)'
,2017-07-20 20:26:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [5, 15, 34, 51, 64]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [5, 15, 34, 51]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-20 20:26:39 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB94D05F-0832-4170-8059-233820381033
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB94D05F-0832-4170-8059-233820381033 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] Session.startOutputStream(with:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,5 [5, 15, 34, 51, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,65
[ThaliCore] VirtualSocket.deinit vsID:65 [5, 15, 34, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserR,elay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] Session.startOutputStream(with:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,6 [5, 15, 34, 51, 66]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [5, 15, 34, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Advertiser: session connected Peer(uuid: "5E079B7C-5E99-4561-83E0-A4660711AA6F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:54928
[ThaliCore] Session.disconnect() peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:26:42 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:26:42 - WARN thaliNotificatio,nClient: 'peer is not available'
2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-20 20:26:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "671A5B41-0FE3-43CA-96C3-FB13B9B80FEC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54959
2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":5495,9}'
,2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 086240B2-409F-45A5-A6CA-A35C459065A0 (syncValue: 14)'
2017-07-20 20:26:42 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", g,eneration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconne,cted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [5, 15, 34, 51, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:67
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [5, 15, 34, 51]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:671A5B41-0FE3-43CA-96C3-FB13B9B80FEC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [5, 15, 34, 51, 68]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:68
,[ThaliCore] VirtualSocket.deinit vsID:68 [5, 15, 34, 51]
,[ThaliCore] Session.session(_:peer:didChange:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54911
[ThaliCore] Session.disconnect() peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}]'
2017-07-20 20:26:43 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","generation":0}'
,2017-07-20 20:26:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-20 20:26:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 20:26:43 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:62F06A67-2CE4-45E5-A0FC-92F2D2005E35 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3F90916C-93B2-4AEA-A154-B951CA01BF30", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] Sessio,n.deinit peer:02E6368A-6618-4DE1-A18F-705B5838DD0E
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
,[ThaliCore] Session.session(_:peer:didChange:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Session.startOutputStream(with:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,9 [5, 15, 34, 51, 69]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:69
[ThaliCore] VirtualSocket.closeStreams() vsID:69
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,69
[ThaliCore] VirtualSocket.deinit vsID:69 [5, 15, 34, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserR,elay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] Session.startOutputStream(with:) peer:53DE61CE-5475-42F2-8A38-39B8BA103AD5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7,0 [5, 15, 34, 51, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,70
[ThaliCore] VirtualSocket.deinit vsID:70 [5, 15, 34, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserR,elay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54966
,2017-07-20 20:26:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":54966}'
,2017-07-20 20:26:45 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F582-40E9-402A-9159-D09698B7BF1C (syncValue: 15)'
,2017-07-20 20:26:45 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:71 [5, 15, 34, 51, 71]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:71
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:71
[ThaliCore] VirtualSocket.deinit vsID:71 [5, 15, 34, 51]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:72 [5, 15, 34, 51, 72]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-20 20:26:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:72
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:72
[ThaliCore] VirtualSocket.deinit vsID:72 [5, 15, 34, 51]
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B3A4F582,-40E9-402A-9159-D09698B7BF1C error: max retries exceeded
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":"Connection could not be established","portNumber":null}'
2017-07-20 20:26:55 - DEBUG thaliMob,ileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer avai,l,ability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wi,th {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-40,2A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A89418E0-73C5-49E6-9EE7-B3AAB0664285 (syncValue: 16)'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A89418E0-73C5-49E6-9EE7-B3AAB0664285", generation: 0)
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16","error":"Peer is unavailable","portNumber":null}'
2017-07-,20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B3A4F,582-40E9-402A-9159-D09698B7BF1C (syncValue: 17)'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7B,F,1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 20:26:55 - DEBUG thaliPeerPoolDefault: 'Got err  , Connection could not be established'
2017-07-20 20:26:55 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09,698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connecti,o,nType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"ge,neration":0,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"gen,eration":0,"newAddressPort":false}'
2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true,}'
2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-,0,7-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-20 20:26:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-20 20:26:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A89418E0-73C5-49E6-9EE7-B3AAB0664285","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
2017-07-20 20:26:56 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}]'
2017-07-20 20:26:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","generation":0}'
,2017-07-20 20:26:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 20:26:56 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3A4F582-40E9-402A-9159-D09698B7BF1C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17","error":"Peer is unavailable","portNumber":null}'
2017-07-,20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 20:26:58 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5E079B7C-5E99-4561-83E0-A4660711AA6F
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
[ThaliCore] BrowserManager.disconnect peer:A89418E0-73C5-49E6-9EE7-B3AAB0664285
2017-07-20 20:26:58 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerU,navailable - Emitting {"peerIdentifier":"B3A4F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 20:26:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable, {"peerIdentifier":"671A5B41-0FE3-43CA-96C3-FB13B9B80FEC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:26:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerId,e,ntifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B3A4,F582-40E9-402A-9159-D09698B7BF1C","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 20:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":t,rue,"advertisingActive":false}'
2017-07-20 20:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArgum,ents":{}})'
2017-07-20 20:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:26:58 - DEBUG thal,i,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:26:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.disconnect peer:B3A4F582-40E9-402A-9159-D09698B7BF1C
,ok 870 passed
,[ThaliCore] Session.deinit peer:B3A4F582-40E9-402A-9159-D09698B7BF1C:0
[ThaliCore] BrowserRelay.deinit
# teardown
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
,2017-07-20 20:27:05 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:06 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:07 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 920 verify failed
,ok 921 constructor called once
,ok 922 constructor called with right args
ok 923 match start arg
ok 924 start called once
,ok 925 stop called once
,ok 926 stop after start
,# teardown
,# setup
,# Three peers, one not in DB, one behind and one ahead
,2017-07-20 20:27:09 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:09 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 934 verify failed
ok 935 constructor called once
,ok 936 constructor called with right args
,ok 937 match start arg
ok 938 start called once
,ok 939 stop called once
,ok 940 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:10 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 941 verify failed
ok 942 constructor called once
ok 943 constructor called with right args
ok 944 last start ,before stop
ok 945 empty first start
ok 946 full second start
ok 947 only 2 timers
# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 948 verify failed
ok 949 constructor called once
ok 950 constructor called with right args
ok 951 start befor,e stop
ok 952 We got at least 3 calls to start
ok 953 at least 3
ok 954 default 1
ok 955 1 run
ok 956 default 2
ok 957 2 run
ok 958 default 3
# teardown
,# setup
,# start and stop and start and stop
,ok 959 start out null
,2017-07-20 20:27:11 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 960 back to null
,2017-07-20 20:27:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-20 20:27:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 968 verify failed
,ok 969 constructor called once
,ok 970 constructor called with right args
,ok 971 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-20 20:27:13 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 972 verify failed
,ok 973 constructor called once
,ok 974 constructor called with right args
,ok 975 (unnamed assert)
,ok 976 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-20 20:27:14 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 977 verify failed
,ok 978 constructor called once
,ok 979 constructor called with right args
,ok 980 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-20 20:27:15 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 981 verify failed
,ok 982 constructor called once
,ok 983 constructor called with right args
,ok 984 start before stop
,# teardown
,# setup
,# test calculateSeqPointKeyId
,ok 985 should be equal
,ok 986 should be equal
,# teardown
,# setup
,# #_doImmediateSeqUpdate - server is not there
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:27:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 987 Got right error
# teardown
,2017-07-20 20:27:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-20 20:27:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 988 Got socket hang up
# teardown
,2017-07-20 20:27:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-20 20:27:16 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 989 Got 500 as expected
# teardown
,2017-07-20 20:27:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-07-20 20:27:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 992 should be equal
,ok 993 revs are equal
,# teardown
,2017-07-20 20:27:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 994 should be equal
,ok 995 revs are equal
,ok 996 should be equal
,ok 997 revs are equal
,ok 998 should be equal
,ok 999 revs are equal
,# teardown
,2017-07-20 20:27:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/A,1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/A1B93BFF-,AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-20 20:27:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/A,1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/A1B93BFF-,AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-20 20:27:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-20 20:27:25 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1002 stop caused us to fail
,ok 1003 We specifically failed on a stop before put
,# teardown
,2017-07-20 20:27:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1004 failed due to stop
,ok 1005 failed due to stop
,# teardown
,2017-07-20 20:27:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1006 should be equal
,# teardown
,2017-07-20 20:27:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-20 20:27:29 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 1007 Expected bad seq error
,# teardown
,2017-07-20 20:27:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
ok 1009 Timer was cancelled
,ok 1010 should be equal
,# teardown
,2017-07-20 20:27:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1011 One go and one blocked
,ok 1012 All blocked
,ok 1013 Still blocked
,ok 1014 should be equal
,# teardown
,2017-07-20 20:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1015 We waited long enough
,ok 1016 should be equal
,# teardown
,2017-07-20 20:27:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1017 Should have gotten same timer promise
ok 1018 Still same timer promise
,ok 1019 We waited long enough
,ok 1020 should be equal
,# teardown
,2017-07-20 20:27:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-20 20:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-20 20:27:41 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:41 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'listening 55048'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A2A9682-EEA6-44C8-AAA3-EC5E3F7FFD2E
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
2017-07-20 20:27:41 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BEDA5B0E-5E5D-4CC6-A843-A28F116E4BAD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BEDA5B0E-5E5D-4CC6-A843-A28F116E4BAD
2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:41 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}]'
2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 20:27:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 086240B2-409F-45A5-A6CA-A35C459065A0 (syncValue: 18)'
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0) found active relay
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"18","error":null,"portNumber":54966}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,ok 1046 ThaliMobile.start was called once
,ok 1047 ThaliMobile.start was called with 3 arguments
,ok 1048 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
,ok 1049 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
,ok 1050 ThaliMobile.start was called with 'networkType' as 3-st argument
,ok 1051 ThaliMobile.startListeningForAdvertisements was called once
ok 1052 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
,ok 1053 ThaliMobile.startUpdateAdvertisingAndListening was called once
,ok 1054 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
,ok 1055 ThaliSendNotificationBasedOnReplication.prototype.start was called once
,ok 1056 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
,ok 1057 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
,ok 1058 ThaliPullReplicationFromNotification.prototype.start was called once
,ok 1059 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
,ok 1060 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
,2017-07-20 20:27:41 - DEBUG thaliManager: 'stopping everything'
,2017-07-20 20:27:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BEDA5B0E-5E5D-4CC6-A843-A28F116E4BAD
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
ok 1062 ThaliMobile.stop was called with 0 arguments
,ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:73 [5, 15, 34, 51, 73]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:73
,[ThaliCore] VirtualSocket exited RunLoop vsID:73
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:73 [5, 15, 34, 51]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] Session.startOutputStream(with:) peer:EB94D05F-0832-4170-8059-233820381033
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:74 [5, 15, 34, 51, 74]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:74
[ThaliCore] VirtualSocket.closeStreams() vsID:74
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:74
[ThaliCore] VirtualSocket.deinit vsID:74 [5, 15, 34, 51]
,# setup
,# test thali manager multiple starts and stops
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1067 expressPouchDB was called once
,ok 1068 expressPouchDB was called with 2 arguments
ok 1069 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 1070 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1071 PouchDB was called once
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
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 55052'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5C78F37F-B859-4E51-9C14-190C7ED9C882
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:27:42 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E982EE16-EF2D-4D65-B990-98AEEB77FAC8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E982EE16-EF2D-4D65-B990-98AEEB77FAC8
2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:42 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E982EE16-EF2D-4D65-B990-98AEEB77FAC8
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-,07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 55054'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9B1A7DA8-5D19-4B25-AE06-41B509068CE7
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "788B8920-FCC5-40FB-9A26-AAA51B25588D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:086240B2-409F-45A5-A6CA-A35C459065A0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "086240B2-409F-45A5-A6CA-A35C459065A0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:788B8920-FCC5-40FB-9A26-AAA51B25588D
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2017-07-20 20:27:42 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:788B8920-FCC5-40FB-9A26-AAA51B25588D
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 20:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}]'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"086240B2-409F-45A5-A6CA-A35C459065A0","generation":0}'
2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 55056'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB644C91-C269-48FF-9408-806BCC550D77
[ThaliCore] Browser.startListening
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1E927E9F-3A86-46ED-9F7A-FAF084741709", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1E927E9F-3A86-46ED-9F7A-FAF084741709
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:42 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-20 20:27:42 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1E927E9F-3A86-46ED-9F7A-FAF084741709
,2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 20:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-20 20:27:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'listening 55058'
2017-07-20 20:27:43 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C4D36690-D78A-4AB1-AB3E-EEE52816DA76
,[ThaliCore] Browser.startListening
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73080C3E-636C-4A5A-8941-CDC1C30CBCBE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:73080C3E-636C-4A5A-8941-CDC1C30CBCBE
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 20:27:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-20 20:27:43 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:73080C3E-636C-4A5A-8941-CDC1C30CBCBE
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 20:27:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 20:27:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 20:27:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test write
,2017-07-20 20:27:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'test write''
,# teardown
,# setup
,# test repeat write 1
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-20 20:,27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-20 20:27:44 - INF,O CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER res,ult: passed - another'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***,TEST_LOGGER result: passed - test sinon sansbox spy'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox, stub override'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-20, 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-20 20:27:44 - INFO CoordinatedClient: '*,**TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
2017-07-20 20:27:44 - INFO Coord,inatedClient: '***TEST_LOGGER result: passed - Can shift data'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER re,sult: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replic,ation actions for same peerID'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
2017-07-20 20:27:44 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - Server always returns 401'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passe,d - Make sure docs replicate with remote db with same name as local db'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
2017-07-20 20:27:44 - INFO C,oordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
2017-07-20 20:27:44 - INFO CoordinatedClient:, '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replication action test - each device has different local db name'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Coordinated replic,ation action test - should throw error when wrong remote db name is provided'
2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - compareBufferArrays'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call start twice and get error'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and make sure it runs'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is right after start'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -1 after function is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test TransientState'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - No peers and empty database'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer and empty DB'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set behind current seq'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set equal to current seq'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One peer with _Local set ahead of current seq (and no this should not happen)'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Three peers, one not in DB, one behind and one ahead'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - More than maximum peers, make sure we only send maximum allowed'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two peers with empty DB, update the doc'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - add doc and make sure tokens refresh when they expire'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two different starts in a row'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two stops and a start and two stops'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we properly enqueue requests so no then needed'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test calculateSeqPointKeyId'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated seq test'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager spies'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test thali manager multiple starts and stops'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test write'
,2017-07-20 20:27:44 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - test repeat write 1, error: 'TypeError: thaliManager is undefined', stack: 'testRepeatWrite/<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/Tha,liTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js:285:7
CoordinatedClient.prototype._processEvent/</<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:471:9
canc,ellationExecute@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/debuggability.js:320:9
module.exports/Promise.prototype._resolveFromExecutor@/private/var/containers/,Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:481:13
Promise@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modul,es/bluebird/js/release/promise.js:77:9
CoordinatedClient.prototype._processEvent/<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:428:14
tryCatcher@/private/var/containers,/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-,FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/,bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.expor,ts/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13
Async.prototype._drainQueue@/private/var/containers/Bundle/App,lication/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:138:13
Async.prototype._drainQueues@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/n,ode_modules/bluebird/js/release/async.js:148:5
Async/this.drainQueues@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/async.js:17:9
$v@timers.js:364:1
''
2017-07-,20 20:27:44 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 20:30:44 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-20 20:30:45 - DEBUG CoordinatedClient: 'test client failed'
2017-07-20 20:30:45 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, ,event: 'run_test repeat write 1_finished', test: 'test repeat write 1'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/A1B93BFF-,AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/socket.,i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Applic,ation/A1B93BFF-AA52-4063-8013-FFF6B421AD3C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-20 20:30:45 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
