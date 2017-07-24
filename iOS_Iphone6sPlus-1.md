#### Test 113351851dc08641_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C37BF5F1-24C2-4A97-A870-52147D55835B/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/C37BF5F1-24C2-4A97-A870-52147D55835B/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851dc08641/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49608"
,(lldb)     command script import "/tmp/C37BF5F1-24C2-4A97-A870-52147D55835B/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:47:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E7B3C763-E6FA-4DCD-B580-67438851EDAC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E7B3C763-E6FA-4DCD-B580-67438851EDAC
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserMana,ger.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A47CF66-0489-41B6-A8E1-26A5D701F0CA
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOn,StartListening finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3E60F5B8-3FDB-4F41-B5A7-F7C886CC96B5
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "50BE68ED-618D-4100-8D0A-4A89B767CC1F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:50BE68ED-618D-4100-8D0A-4A89B767CC1F
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:50BE68ED-618D-4100-8D0A-4A89B767CC1F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "50BE68ED-618D-4100-8D0A-4A89B767CC1F", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-24 06:47:22 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.613205909729004
,2017-07-24 06:47:22 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-24 06:47:22 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:50BE68ED-618D-4100-8D0A-4A89B767CC1F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "50BE68ED-618D-4100-8D0A-4A89B767CC1F", generation: 0)
,2017-07-24 06:47:23 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 06:47:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 06:47:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 06:47:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 06:47:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 06:47:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 06:47:25 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 06:49:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 06:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
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
,2017-07-24 06:49:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 06:49:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 8 should be equal
,ok 9 should be equal
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
ok 25 thirdPromise - in resolve
,ok 26 secondPromise - second to run
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
,ok 36 firstPromise - in catch
,ok 37 third
,ok 38 thirdPromise - in then
,ok 39 testingPromises
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
,ok 52 test participant has uuid
ok 53 participant data matches
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
,2017-07-24 06:50:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 06:50:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:74B61748-91C1-48A0-8B27-93BED78E568E
[ThaliCore] Browser.startListening
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:50:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:01 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CCDE7039-93AF-4406-A196-F697AFAD7D83
[ThaliCore] Browser.startListening
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:03 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5D87279D-A3D2-48BA-ABD7-BBC03B88DA91", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5D87279D-A3D2-48BA-ABD7-BBC03B88DA91
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5D87279D-A3D2-48BA-ABD7-BBC03B88DA91
2017-07-24 06:50:04 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTyp,e":null}})'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:5,0:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB
[ThaliCore] Advertiser.s,topAdvertising() peerID:C23FA51F-D64F-4DF0-B2DA-01687CE2A0FB
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:05 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6A12CD7D-7950-4B6B-B5CF-8B3408D52793", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6A12CD7D-7950-4B6B-B5CF-8B3408D52793
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FD61FBBF-11AD-4D80-A46B-E41612B93338
[ThaliCore] Browser.startListening
2017-07-24 06:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-24 06:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6A12CD7D-7950-4B6B-B5CF-8B3408D52793:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6A12CD7D-7950-4B6B-B5CF-8B3408D52793", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F282B8DC-7DA4-4681-A8A8-6F2EE2259EF7", generation: 0)
ok 76 peers must be an array
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB8CA58-4E4A-49E1-9E9D-9EF17B37AB2E", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:50:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6A12CD7D-7950-4B6B-B5CF-8,B3408D52793
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A8B1D4F7-116E-489E-90A9-6E13E0070383
2017-07-24 0,6:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F9DFD667-2284-45B8-A906-89AA2F28FD1E
[Thal,i,Core] Browser.startListening
2017-07-24 06:50:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:50:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:17 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
2017-07-24 06:50:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","generation":0}'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4AD769C-CE08-4F9C-9F77-256A14CEDA92, (syncValue: vtXwrxXNwwAE7HeJl787Gi4Epv4cSYVk)'
2017-07-24 06:50:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14C,EDA92", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A
[ThaliCore] Advertiser: session connected Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
2017-07-24 06:50:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","generation":0}'
2017-07-24 06:50:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8B1D4F7-116E-489E-90A9-6E13E0070383:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58901
2017-07-24 06:50:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vtXwrxXNwwAE7HeJl787Gi4Epv4cSYVk","error":null,"portN,umber":58901}'
2017-07-24 06:50:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vtXwrxXNwwAE7HeJl787Gi4Epv4cSYVk', error: 'null', listeningPort: '58901''
,2017-07-24 06:50:21 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A8B1D4F7-116E-489E-90A9-6E13E0070383", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisc,onnectClients() port:58901
[ThaliCore] Session.disconnect() peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vtXwrxXNwwAE7HeJl787Gi4Epv4cSYVk","error":"Session disconnected","portNumber":null}'
2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availabili,ty changed event with {"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not bei,ng in started state'
2017-07-24 06:50:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 06:50:,25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-24 06:50:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:A8B1D4F7-116E-489E-90A9-6E13E0070383
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92
2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method ,discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:281373AD-3A04-4E63-8025-EA0CD6FB0A44
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:283211BA-FD1D-4342-BFAF-C3135477885A
,[ThaliCore] Browser.startListening
,2017-07-24 06:50:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 06:50:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:AC1CBB10-3E06-42D3-BDFF-8D59AC58356A
,[ThaliCore] Session.deinit peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E6B3DB7-E302-4E55-B5BA-67F66946C1AC, (syncValue: EkrbdiW07R5MOgMUoKvVV15rpekzhrbA)'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F6694,6C1AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"D4AD769C-CE08-4F9C-9F77-256A14CEDA92","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] ,Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:281373AD-3A04-4E63-8025-EA0CD6FB0A44:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","generation":0}'
2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83026883-B6BD-420E-91E3-BE6D772339D8","generation":0}'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F
[ThaliCore] Advertiser: session connected Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F state: notConnected -> connecting
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F
,[ThaliCore] Session.session(_:peer:didChange:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.sessio,n,(_:didReceive:withName:fromPeer:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F
[ThaliCore] Session.startOutputStream(with:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient,.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-24 06:50:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D4AD769C-CE08-4F9C-9F77-256A14CEDA92:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D4AD769C-CE08-4F9C-9F77-256A14CEDA92", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E,6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] Advertiser: session connected Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1E6B3DB7,-E302-4E55-B5BA-67F66946C1AC error: max retries exceeded
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EkrbdiW07R5MOgMUoKvVV15rpekzhrbA","error":"Connection could not be established","portNumber":null}'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EkrbdiW07R5MOgMUoKvVV15rpekzhrbA', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1E6B3DB7-E302-4E55-B5BA-67F66946C1AC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0 (syncValue: 5acejbcOdxmZWjSL4TbjKRzrk5UbvTbP)'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] Session.startOutputStream(with:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-24 06:50:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2,
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E6B3DB7-E302-4E55-B5BA-67F66946C1AC:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E6B3DB7-E302-4E55-B5BA-67F66946C1AC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58910
,2017-07-24 06:50:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5acejbcOdxmZWjSL4TbjKRzrk5UbvTbP","error":null,"portNumber":58910}'
,2017-07-24 06:50:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5acejbcOdxmZWjSL4TbjKRzrk5UbvTbP', error: 'null', listeningPort: '58910''
,Connecting to the localhost:58910
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,Connected to the localhost:58910
,2017-07-24 06:50:41 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 06:50:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
,2017-07-24 06:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:281373AD-3A04-4E63-8025-EA0CD6FB0A44
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58910
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0", generation: 0)
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A02EEEB-6418-4117-AFED-AAEA38183F15 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5acejbcOdxmZWjSL4TbjKRzrk5UbvTbP","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:97B785C4-BC77-4AA0-8E3E-C83C1EC0915F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "281373AD-3A04-4E63-8025-EA0CD6FB0A44", generation: 0)
,[ThaliCore] Session.deinit peer:2A02EEEB-6418-4117-AFED-AAEA38183F15
[ThaliCore] Session.deinit peer:90E5B58F-B1BF-40A1-8EAA-0CEFE86BBFC0:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7DC295B6-5886-44D5-B750-7B97D55E9F06
2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:42, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 06:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:34FB8219-BBCD-46F8-95E2-21B8373C5687
[ThaliCore] Browser.startListening
2017-07-24 06:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
,2017-07-24 06:50:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83026883-B6BD-420E-91E3-BE6D772339D8","generation":0}'
,2017-07-24 06:50:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83026883-B6BD-420E-91E3-BE6D772339D8 (syncValue: TcULaU8bdGUO2tPWe9xlSx4BEEaakIiw)'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","generation":0}'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
2017-07-24 06:50:44 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:44 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:50:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7DC295B6-5886-44D5-B750-7B97D55E9F06:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:83026883-B6BD-420E-91E3-BE6D772339D8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,3026883-B6BD-420E-91E3-BE6D772339D8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:83026883-B6BD-420E-91E3-BE6D772339D8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:83,026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,3026883-B6BD-420E-91E3-BE6D772339D8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83026883-B6BD-420E-91E3-BE6D772339D8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] Advertiser: session connected Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D state: notConnected -> connecting
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TcULaU8bdGUO2tPWe9xlSx4BEEaakIiw","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TcULaU8bdGUO2tPWe9xlSx4BEEaakIiw', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"83026883-B6BD-420E-91E3-BE6D772339D8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"83026883-B6BD-420E-91E3-BE6D772339D8","peerAvailable":true,"portNumber":null,"recreated,":true}'
2017-07-24 06:50:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:50:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C64B7CA2-74CB-48B1-B1C0-43A726C4E62F (syncValue: G6w5sFm9R7tVQLrf3tyaERa,KAwjdZrGJ)'
2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C64B7CA2-74CB-48B1-B1C0-43A72,6C4E62F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:50:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:83026883-B6BD-420E-91E3-BE6D772339D8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
,[ThaliCore] Session.session(_:peer:didChange:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58918
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1,D
[ThaliCore] Session.startOutputStream(with:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
2017-07-24 06:50:52 - DEBUG thaliMobileNativ,eWrapper: 'multiConnectResolved: {"syncValue":"G6w5sFm9R7tVQLrf3tyaERaKAwjdZrGJ","error":null,"portNumber":58918}'
2017-07-24 06:50:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'G6w5sFm9R7tVQLrf3tyaERaKAwjdZrGJ', error: 'null', listeningPort: '58918''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] Session.startOutputStream(with:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D
[ThaliCore] Session.startOutputStream(with:) peer:359AA5C2-7450-4B43-8EBC-C7325FE0,6F1D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
Connecting to the localhost:58918
,Connecting to the localhost:58918
,Connecting to the localhost:58918
,Connected to the localhost:58918
Connected to the localhost:58918
,Connected to the localhost:58918
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 5, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 5, 6, 7, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-24 06:50:52 - DEBUG testThaliMobileNative: 'Server received all data: QW56sFY80b8rCh4e641SOQMBQUxKOAUvScb3qXNi0nt4tojRUt29P9xR4wr6HAu4XXnUKjh9JbyqJO8quEtkNgKP67F6JuvjrChWZqp8KT3i1jOsVqyvwApjuMBdgN4MHmHaS9VDSYqjBOyNrkSd0mBZdDEPuw7VQf5SEad13C4zSwgNXE,ltO1goXWKNDIM70QUNynCKI66HsXiGCPdv4mQiB7Y5GOyfy9tX21dCfE942IVsZqbrrlN2LOvFBWKITQaqB2Kx8ILS6lyya7fuIOJahbw1syAYiF0oMoojtz594tVcEAJVucKMNXvRkjsyhfDHxTw6Fd0gtk6CL3dMz6ReEVpwhgFK7ie3MrnsqZpXtWW11qDMyDKQABfSFnm91YIe8fcuWP36m2eLuvpHJkkiMRXfug3KgJWO9Fw6nCPotnZ8Nx,Hz4s3iRBTliaF0Z9NbVEdtYEWNEHrRpGqbeLAKsngpjzGDZkskE46eznf8oAABjEouTwXIcwgF8uJdLrUM8Ynabl9ju3NPtT1muA9K77rPCm5R8ARYOr1p22G20VWeKf1c4WwsH3mB248X0XlJTeO8AYbNCZe01cew1m9xkxCyMhiRYBox0h8xv70t8DiBMNPm0zxsgDXtjDExOzT65A8KXBAJLEyem66ulAiGY9PtlUcZQbkoJw2EgHiQoi1Fqb,ewHKiAI25k3nTiHvKDk4pKa21uHQy38b3fGhnHwDDdwIClcuNmoEWqQ9vCEgXrdSKrJZRsyDUZgVezwI0HOXWdw2nglmYcf6v0Gg6O8NTDixfblJb7aLir1Ya77V6YxAkCqYWlmNAIOg2YBP1O21LiLl3500JHBgd1raQmCPLrB6PpyNYnlRTLc02KsaocYVXHxZCq7rI0t4xq9Z2vFX67ESstjsG9jZFMXi6FrUauwmEIGzxv2f37CvfBMP7xN,W,gkdGKhPLrNwjwbVTUd5o763SVjrA0ZQ0szdXLsTEZhWz1dQa6YkaH94BvmSriUlhbwiV5bDWTEDqVLrb2x0HEtWyq5dX0tfxN8YKOgR41oXX9bqpnWv9W1wXeXpb2aDs8lw72indYUt93VdvfFN7HfM0vwZwFnCV2LwMAED3NPtMGOMfxeLrfZbNsI6tsccp3b5tNvCgdwAYWlr9c6tf7oAehs34yVHn0LsHObmMdeRD8qEtWUeBbSMe6go0ohll,nlLBjJldXNJ2b4AyW16StAfCeZm9rNAbA34Y8bYs49FDB1woc8FgYyb5rKPUBhftZzi1yFmyP7gIRv6OveV6dI5L3JJ7TOXzDGWEX8w3SR043X445I1kuxmZm8O8UcwJ5PPuwBk8UUT1jriNv8w4osFfnzFCir8HvbaYQ7j2YJtQ3uqFJGMpCZpJwTzlD2r1Pwwhizk4iHFZ2EjmrQgsb5wCfWzZ9hFOyepKrmectfuz72d4GEREQ4JD04IYenJv,PqzsZKaCtQXZdaxeM6izVBumBUPVapozP8EieYwio2bGj3fYdl8DRCNtAIu4la6ecQDC4sNxw3Nvxt5vUEbNX6TM1VDyRo1lvWzpJtcBIlvaKGerps1LGwFWnB0hpg0bUgwRuN3tCiB8rvio0tRIrPmStyAyymRFILkZADn1RktySXXBxTIUrKChqi25JcJIdyxRkZ5goCZjocSUDZJvKMaeiu0WicGhZ4UDj6BtIfvqyo1IMPfvF5ok1MddCfSE,B8GbR1Zw9TpdCObNsrfz1NpiS8DU2ba0CeVA56K26O4xIwaAroB76y8cmEQ3soy75kRG6dPLi1bzZEJIYiP2NL2ckR3qcODUeKNtBDCIKLjnZcMxSwDz9RcOwpcC0C4kVRmHgmUk41vTsLoi5BFIWtnXK8ZlbIzAWgMj1tyZb3PNDbtTJO9ShxhsIs1sOisVsJQpUu0mzlhBZdssD3wiONks0wdc32nC5HOS6v29hJHBgcYjrRnoHq9H4Fh5GVC,h,FzPjbUs9PUM6yVTv5V7qWopfdMkcFZmSqvJk1q1P7l46nPKMywGlyo1Mkxt2vYT11XFJG8aNMfUSgl05pjw1qHqLD9FQ5CAtnJotDI6dyxVsklxHXDNdhAvpFgd5HYIW7RKCYSk8KUuAiE1d1f0bVGWJwBbWCQ19jzsztM8wVrYZckep3ah1cU9RfscGhkp2Tq1mG3CRVvKS2asegwpCGDx7XOD1uJl4wJvH2efk37hscsrUrQ3Q7g6jhChla6ic,hdCGrOlnU5xTjsxO3nADN5h7IkEbMbi0kWlta2lNmIwnK2oJ6yErA6AVJZdErUUFZ0p0mFlao6Wy6kvFan9ARd52DGbZrK1zKYF2TdnD6rp6CoY2zTcFi4UHeZjrBYVG9RZ69K4DSm7DF50K5OhFIx7BXB0QCZty0Wn4JYPpAU8ee3woZIVNvq56SOtgDLwOq3xlicaYgjXfgowZoIDg8pFxO6bs4dnUIy7q9X38EDOx35ar18VRMgabbVDtMBih,DKPeWsWtHI8H6ZUxtL0J8zIFBckYO9gHOrpYDiQXN5sfsT7Obs42AwT8g01uQuiWEIGiZfOtm5tq1gyeAM7CEgXdT2vRHBav6kPgeHvkufUD6V2LuldXB4NAnzdqZtNR26fEdBuaKHp8kdHtEmhZLZ8YiNHSA0XsLJOKNaBRKw8LMQGEY279ICopOm6FRksozGJ8rJ6Qb9XRSyeiDZ53q0PiqnlFijeoV0jrZcLPBKJ1OES18WXMLxAdK8ElXZLt,yFLMBRP2OOS6v8ZeHYBvnGTf5dsZDXAeq5KouMwujVWnHvVnAOtnszwRMIBEkslqLWFWZEk6hnN1X3hcmKpUbUFO8GgJ5hBMe5zsoRzZKsDPfAHC7440p7h7eSa03tS4wM9J7GPn7fZbs3WItgi4U4A5lbQrNI4UgbYvynUNLN9t1HePilY6Pnt8ibtD5JjFSagebl2tfMyHgStK5CWESuLl8NWRoUHSnryynrWICMIf6zOAOi6Rrc8iAZhehjV,L[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4,
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRela,y.didSocketDisconnectHandler disconnecting:false
YNRWzj9S5KoVZqyCO2YCjCf5O8V2uBXhVZxAYMTRGLpfZxfEF8RNH5qK5LzToNpF72lSQfYs8PxUXFVJ0sZ4CQuKe4ad1zNAsdDrsxo5RcT82TxI8uAv5cuLTn63ibipGqTE1J8n710UwVBa8sUgCl0MHUIuVvtbOVsThNc0HnzxWAs2KNxj1rxBWZl9DqGeNbILUHcI4stjQ5,LGZOsoB01ZozCwkIfTRzblrmGGGZZkF4YATyU6IzkscEybYkp4xQ8aWFSGNI6odxEVuIfW7CjvThp2ZpwbXxQl2vY43cnvds47YWJD2uM6E9e4j7JoU94pnM7IPyYgWj6WDXhuxtftPm5af3AgInFLnY6xMREVPcPCNOhZaZZ5EdDVeP1VhifqnuMKRpDuRM8gVJcZ5EhrWEpxwFS6mu8KQtZ3n5MJo6S33KCab2RTKqatQp7wBHJTCKhWswPJN,L,cFzox0Vw1ENJy2f4gtnZslfnjLgVYNO00Kq8DftT6jahbFS2h2pf9qrkc4MLVT9HfwGWOGRn2gXrhVgWEMfzuLkd76QoPVJFTz1pgrMdsjiOkJwLf0uXXdftRO6GxzoheHhpjfn9muhGzz6yw5PyC55GCVBYS6N59mVAWlTIlTQ0lTEuPZRljSVJreB5dv3RZJ1kUNpUYvATqZtM85s3qFGnXBhvo86AmN1STJkRuV9V9Hge40lA088pmeCn0sf1,r4SojScUdSYwFqDi0TZXOejntlvlFABuvO2ioJC5Srb2eGAODWoTl58cXPZxPJTvwNPJsZ5jvuhEMUDy1aUYJGuFSgOLk9AnTA74SbyPOLG1Uzg1K4szfapvTUHRFDidz4mYH1LN1BD6pIxawR7CdcrerMYQUGPgYh7NZYzn6vO3RrROg0sTZFvxrz3H3PF42mwp6DgoGwPFDSv2b7yvyJSmU2TrCJ2Q9iYQtQxzSN2rhFBM25P2T1SdreITShxG,g2gPmGQqkKKCXVEkSFJcFzAmUgWLY5oWNlRNR9WAXBlunmUjN2fC1VrZyUvGgYsYE3vEPBy138ouPaB4VvtxwD2Az33VnzQgwIMjOErh7zKcnmroG49ZuOVRE4SLfDEuy3K0nBx7KRc1DlaryAHIKSg7fq8jym9vPocUKDahoyOjDmYIpvwgjJ02eQWzn8X9uXw12kTO5NgRZHpaRhb8FM9k0MeZRUXdkLwMBGeKdOuu1EvUtewuG7u4cIArnh65,gGfFPk9VEYcBdccUDSL8Gy1aABIB5C0pgOChrPXmemoVICZCcOZn0CiRAMZ93ATattc8rExcb0wJxndCqo7lipzkX72AyI7HbDEk5dD63oPxXkDD3BhieM0xahHwMYY1BKfBJRSRXRudK21zY7D8PiCbMl6EvpnAUN4MDde6yIh9nyGK6UM0WcHz0niUjE9hFErOEhxa8hkvyOsu0JaugKVV0ViaHP3wvPxI4WRMbz8dohzEoxDEZZRhWjoAywR,e,UjIyyjBLxDrbKkYL5ks9t3ZSDjIwb5mFD3PzoJDyaLrUnKrrOEBYumWRRkVrXhGaSFfzfczH5aheJkSALhxUeaAaDzLqoasliIZy5XVoNosdaymy8UmtCCRggrBJ5tc5ohWBTPWsL4mdhRU5A4ruTZGlFnVlNFh4gPph8PmkAecn1zqNCV2TV0uwuA8OFKzzH25uO2yd9uVW4BkAIYRzUzP3IBmMzj7sri4ZpIDrnb2W8JgdzQsz165uO1V4R5ax,4WbLzxilZRcAx7bTuyeFfmPgjTsSfShILAJVmlNUugRVYOgAJvJxASoNHjzWxwuIjOLC2GuwDf3Xck5RNoV22U4pSb2pWb5Vq5eCbMSLZHuQmlSY6NIuqSIaZFtIUHbHqNISCP1cUQVCNMOD4stpEHNKMRva5B96mfkrOWji86F0kuLMBmcKsp35FkQclnU2h3Rlp693jhjsQLRRxIDVgWdB6XuRGDllSzSBZAS1hwrFDeeSfADbQL9vbOBccQ85,aWthSsHvgj808pIjaBHpfVXL1kb2hiXnAiGhIhLNEK8u7j1piO4KSrb4m1ksvMO47Oet02JGKHEeFT58NcWGeTi36KXYokGoo9PLoIqRxHotch06ac2NKLDyGE9qMYrqFmi8U3O8vJUE52AWcwJzwuKOewU5vb5xa9ajcbpfUa6T0EKAjMpOHYISpVDXYFjeMKuPnqsbEY3WLRJ9Y9spoIU5OVf2pEbN0FEjkql5KEXlEmRgANiI1AtvGqvUd4kR,93dFXBr1a9NWsBXLyDOSr74x1OXGrlr2pGZCYeYamrLI41Y02iL8hzYEzeLKWB3dyvE2bGnabAzXRT1JlvagY2u1uCFvs8HcNb1PzLw1lNZLJUPLk969JL7kaW6mZ71B0umi13MpLzx6bhlhVut1ZGQt2sKhkJOxYY99RKySzmlQ7QrOAgUzoltE4Fz9SVDqMGAQI0nJVr7rlnwpwvKxLmNNjBs1ZB8882K53Tn5QiRzy3cFp4g4D9gci3l5jZY,R,1tHdpY0fCXSs8aE4Zyp8xC7eGWOhAuQlvWb8pKaivzMwjM4WMnk6Ef3VEygvK224WcmZ3qLADsVLvcd0urQip1ILhyfjIZ5ZiB6ljaNgX0rbzhfFNvJOEWv8GfyhYR8xnHTS5XhORw3KPrcZOKrujPcZqqohVRtso69ONFZodP8snKWaq1YiamiwAzn26ZHs9NRrGGE96g6Zuh41us9Fq7EU1sS70aqIu1kEl0nkFFMRP84RhjVTkDHhrnCHrfBq,wxJypyvMSx9x3q36FpUsVLJJVcUeUOAASb5dQMsmN9OsMqoMO0rAMRvqQN6WcXFul5czSablcPlk9aNhISVsoaONTGPtg9zk8dMKow8zOLy0fxY6W6O42nSoSSVcNvHhkuV67jYKWTqLdspFYrDCKJ77j3wf0oVNWOBWE5lUR2v6MlMcHp3eGYa3prqd5L7JlJoqYr1NLHabZdWIQ4WDLwjvBsSoNaNoJw5PdV8qHm0MxlO7lxuDY0d48tEd9t6C,CVoZOFIkTyXW4HCOei5ugzRWSKXObkQ0uFSrCgSgRNpe9UeQQtSYJjx8Xm25BNBdBQQ10mBhvhELajuxwlyFZKJAjXReGtEHPrsDxdI4s9yhWNnMoXFH9WHys14Ol7r3LgjxDrH92nWXbkJBfnXzvw31ABgtG3wkKObpRD1wer18zKHXKgzGG8eFC3XiNciyvrizTTrAUMe8tFh0CKnfUJSWVnG1q55mut4RYBA6W80KqTbLx8Bk3TqRxg4fYJaP,pfTyzaaOdjYGPXT0yX5Xe94azfMW89ll9QpuF6dEMA6pj03idLs8YkBYT1QMp36MbDIxHDlKehgifzKBmrQUI9gOYDlFFdKYs08dvSXcVPe2sxP5EE2U2Y3Q8pgz9u5H4SsDjVHTVGZJbOWZ0Gx1VUgKwriYteIHR6N3PWd5qUFJaUsnQ02CsKLF72WxOuuPkLeHjysles8QroZVB3KWF0YFRYnbL2WijVN6sJqWDrpZts50VEJtpbORU9UKhJk,q,m3RAwWSMGnPaZmdbHFbFj8HkF1Nzavg3CbbqyYvoQ1VFtSUhrspcYTeSEycpoOC8wX5kZBLg6U0CCAJOhBiQx304BoI7W6hT84CKIR7TSB9v7r5UIWGgXy16xb3uGpluq50lVO4G3iyLhVbYdAT9QH4X4mwMA4Tagwcbepftw0qpC4SOQ7GpyTZ0Lq3ChsLrNTY1Fu4Kgmb8cJcSvHZd0STHe5p9WQJyA06F6rxTDblRIFLdQwOl6Hj5HCWoAyKD,LHKMNxil8unuh2wCbAGJLuzPOpqZPBZLK0v4nh8jhYnaslKnB1tWdsb9lQ710GWEvEeSfGdHnstbborwAFFqGvk8pb1eCKAa7iGQ4MzbCESUKHrfMPuRaxzLUSgUyFuM3sfH7R6jZWwLfojf02DH22StvD2UDJul0m8IqgeDXJNtbfzNkiANfqjN6LD1VDMVCpVFHdNTitJ5qVA1BbEBPVz0MrGd9IWN9maT17UlgJTNlnF7xI0hIcU1rvamMu8p,MvF4tGyn3h1ZRBgiPwKFR4TdOKzcSPF8Oh9RN73FFq770DQRYYRAwx2GDBRejnz2c5nIMAN68dYyV0bYtjVTrpcagFkM4NmhHpzOxRrNckZYKIuFUCsWQMpdKMwkapzysJeLEc3ABxvrs7xY1hQJrxIPXhPGFtAP34vOsapx23ITxD65lSzhGxQNyQ0OmckctkJHkueZrNodVkmFWWWQgGeEQj0iSWmx4dhDRxMXoMA2Bgy1acAkYwFxm4pYFrDL,Ytwx3Z7q7cejObMEdQjyz8dwObgLoOVcFlfHxIarMqDQr9I7u6z8LfXkCmQshKFKI1jEeuzj7kAvwifu2qIA3VXrQwdxHxNMigyNVKdXuE6yHraOgv87nR35I9xHWskqCrdPU9iahWroMZOiyXw0rSkO43uJd5qTPBC2wLSFqMnlmehe20jeYJPcII6uTNIwTnp4JfrMwBAXHSmUhGjuS6Jwp6hrtcq5O5KDEedOnGlXArVbtYj2Um8BfMnN7i9,J,kOztzDybi27rer6IKwyKzARNO8CVQNrAHvZZgyaZ5k9mWQBDYJ3wUGhS7zzQRMEO57Jmw7iNFCKBce2NurxuV1JMjIEsUZFInnfmiTXG3Cq9gstxwjmyb1XMwWkumyNaVx0SBLYFS7yeIzk6cAM5vohLudVXVCCLQPlPwzBoB3xHJl336b0JXwes1pg53FkLZlcCkEhvbYYSH9qTdnGVw3rcNNDnNXMxKPIZb1vowPNTf9gaqpxhYNlQovsZcEGu,YRnwRWLll43CoPAsRA66aTk9zpGCiqRcinNizkBTTWIQ0yO89cuLUCh8wIzKcz7jy2lxxUr8ezGRGqeUOPH9Lw2UGISNeSv4s6RVBSlf8VvPzu12ZVZl0v0pSlWM3KSs3d70yhuIRoe3HYBiyQjdD7o4BTV4ocwFJDIXKyxsIQNPjXv7gkXEaNVZXfZJkBMAQkaBa6lhflZCa1L2MN0stCC06yxTHilimSRsScLqI2rmoiqL4Ec0sC34qwTQ7lMe,tbx5vpnc4RG0MBJ8ARSJhJIrOscdao96ys8iKpaWsWPC76202cASvrWWHTN26Mcy7EoTC22KpOOTCqaD02zJ9o41qx9I7muaIKeya5h05qxeBasilYGVlYXtGEQByzALz0pGJlfECD0ohbpeK0PtUZJU72dcejcGn6ZfZLYIxiZYX1yJ1irdSB4Aslp8wpBCOyrE5jTSbl45tgeG6wXQm2uzTd7KJ2ydMaE9bCBinWPtmWP591Ou5eWf9SeMPaas,RIuxVixd7SANR9nR1C9TdEXKN2SFSDbC5uiafGtFR92kpyBZfcb2ReYDskv3SYp7Ob1o6lsZuQO0jAP0EJH6MNQtNlOVzvlxLraNn9BSNAq5IIC991QXA7MqnMARBHY6bCbxnHPT0YndQdFElZdHXQicF1dbxZBmCwLCPpFbzeYDzjS0OPdN2QRfIZN7cRocjWhsDwHpwR0v5oejwS23iaVYbkkVSysp4Zds40Pvt6uBKRC8nP0SrEc7ARvAs7s,p,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,Y,Lc0dDlmWYdrZ9Rjmh0RmlgQMSF1qNDrw0Pi8D3h5xiBoP9vWHawjQxCys8oE6G5yhzCvC3ojTYf4J2eZX3W5x4jMsvwEixtcPtCtg1I5Ipn0R93pND7TMCL9LqDhakAM4Dlwxh1QkxEu63Q2V9eKLdHLiWWzRecyhePc3jjnmLvZIDKWXA9hYNx47jGumkPGYYV2PLiAtLXBa2GHgmZcrwoMvikvaIKrLrF7bPCJounhxKxB5zKjTjoqqHk3zqOG,EIKoh4QxQW7qzBCb1sZKEQsEeDN9SneJquKDWX2wQUQE7KikwXZiEF6nAOhOs6Th4Dw1YJhWrZ9jnN2GJgYyym78rLN536PBnP8zBPpyV8qrPP4xmjdWwwrXokDSqcFV9qVrXKsGRVnYLGQF82eltM22QGGpzlas0ueNM4TXJ951go0dNv85YmDV1GKEkzb5G9Nyg4KEbOTxSiLGzg6fyJgX6M2vL3whY9hCWPEP49QD9WlCzWoRXEmPeWXauX3S,ycjCSbHBv5hLk8SUHqon01vYXMdcxQRReujj8tP7kFhP9GbDAPZXlFwe50JBIEmONP7xJvrV7LUGVQFHsYvbL2m5DqrBiGU4uuyUp6KJPeWRiDk9Yu5zWiZh9vrj5HB1CRhTvmwb4ygLu0ncL4ODgYRhQOxz5pJg15k1jwiLuzFS0NjQ5BEwIuPXwIKO3L2Bitt6Kdb88XaEydtGTmCy3sHPgpLESQdy6gS59jqJlgSnrUf0LhSO5pJ3QUnDGifO,IPQVwsGne69xCsts9HL02W9ia3OYN0tS9zUoXGY1xSjcQWHve9wrPkhZ9ejoYDOsIZSXCOujf8TfjxVep0VegQB12HsFJ0QAJCLWltEbrsaYWXBa51b3QGUgUEhmJYSrKKL82IeHVZxm4pJbFldE6zjYB0kHTW9OIcuNGwyyKTJOptnXXpPh0Bg4xmq6SBXcKr6YDebRD3wG4n7bVU8tWAHdvFB6PbprqeqGhS7DHZIOVlbRasSdhLu7Qy5JoIv,4,BjRa7JZkpoq0RThv0Y6vtObHarXbOdadHFxKqCTkqTwhTycoMXCF4peq8XvwHSpNMv4BePSvfQ419lAEF8BFzw71qWk6nxelZTf8lE72vVtW7AdkYIil0SSy0CCh5YQCBRgbiCyqAgM50wMINNGFR2uNuLPVB7eoYo347djsXtpjrhb0HUBiARJSYt4an0DBsAmlhAyfXU7MUwIIvr2INq6GHgEOAPmodzyLLekNR7WPsqjRmk0QucLdzSV0gfJV,Kh2dJGmR7G3S2oNxKJPLJl5GhGUfrvNBM4bkFfDL758q1c37ooSViqFbU5fE6i0N0BC0aKImvUGCwgr3wd2yYerLO1zI630she8tEyQm587SOyUxWJN9snjpWmki9JMZp8CuALc7RLrFaKmiBo0mibvweAkLaubSxd5BFccyhf67z1Zh5ZoF87dqu9Ctkj0GgCuvJheQ3OBSpdnGIWpM9OJAohukK9Zrczjfx0uLD3vb40o5FCmw3oZZKxOb2cn6,Rn1mCFcUXsHuSktq5e7legxBa0tB8bhe1B28dF2DfXmAIquTcK2VKHHzOdWnmNrHMGfGiQvfF7udaj35h7ldwMcFOJMIVFV2TCwi3pXzSNNHQ2ENPp0i0zfEjuTrl62ptBx7E6KuXa3PhPXuWl5zt24N1jFRwRTaUZE1hDqeFi3F2kof0BX2ylsi3g6fevDMpeV4teHCzQ4HCa0ZgsroeBFkfNgs4sEfor7NrQrtTGeRyY5C0QovyldK8g5jvGR5,2E8CCDGponoVXT7Cf9W1U7cqHZydBKR3wyyA4au6hsJ5KSYhFciQ0il952nfQZf14tMk1x3tnaZC6plEpQbRdMKYwJSKqixEHfsDBEcQjHfOiBq89PwNNDF9D2baZX0MCmnUXTC4LTpFkU43xdgqf4jzRWu3oQr6Xxb7z2AXAj66wUcp9Sw3aFEmp6HR0DtU9jTCKV2YIkdIIYDMQYIJcsyC2WztWoL1GKLWP1YvOnoIWropYp9OriP0QBXdrOX,5,NrUP0psiCvAI29XaPahmmSEFgKQ0o5G8wNOvCb8XZal9QNW1RP2GoJzfyddaP0QJuBSYOBGIzDHH1CZQXhltjQAx9W3qP2B62ERxt53P0E40dUaw5ouwgg59gREdmrTTSBnhxb1I3Hded1puhEGiSdAXracrnX6hOGR2Y4YjKnCjyJsw87wN8rAEL2wBEoO8oNzxuXzmiNkoKrikpOPbnsBRryZmjADSJQ62g4oILPpbN1xIxWfSoOgdepWOBOPT,IOtUD92R9rhofYtL9BHhWchw0KzGyl2MBVyOQM1LCLSYa0a3eAkAPVMhjk9WcSpxmUOmV7q9bHB0ufP2Ll2XuW07l20T5P3KzsvIpibhAa031Uvomw929OapM8pHRnd5rlJE0761iKPYiqffvTD0zXKFjhj9vRrDyGc4EXkQFvQygTg0To7rA3MRQrf49NZKgWaFMXv1OclVdqhEFQw1K74D8hqYRAO2mzIbRDbyXfj5bYthe6DA51BGEXdmxUav,f4Lx1qhtDbedn5eelv2yjMzdTJJWSbvbOsN8rUgnISQ7XHIgK8NiAsraISYQQaK9QCVm2mVkAdObq3pkXBjvK0OqxMjViiWl3FYQ7jDjKm9eXZ8cSrEpDxtToLV63HY1lrP2z3Bq0NmkoSO9qVRbR5UBF13L6P1RLbjOb86XwveOA7PkoO4spzB4u5s19rSbrLXHQktakuH3hsAglWdvAxAKIHCd0IQ88RDvKU8vJYta3SvbJupvVlKFuVclQRzW,oJD1HOQiE5iXD4JBOJkGrdR1d6eL2lCsj7JDF2KUei3YJLKHXYsTx4hCIURVOLdNObuyn7YEx9OUmLa6D6pejYuBMlS10NlNpSVknmZGaSQG1cDtiHjt1l6j38FjIh7Sl6oBkBtojYvKAp0R0h73eqG8FGCEjWcb5NT16YYpmTaIDyA1jWYCuLiQWrmeyWszKPq9lCy5i9KRfz7YmGERX4hhnF7FLa0qp5Ae50v7maaqdO6JNSMilpdML5MUnxe,N,DU7oPeXksnJLwlrRCZmUcf90oHKoIdbCzW5UL2UM2QPWkErjbkeZD8xBOZkfVpWP70bmvzlsl4nEa698FnB4BzBCDADXpuVFnIWIaHwf5tyTrpHYIoNgHdHvWQSVIeP4GXKpGnMAVZrloSUCjzOlqGE76EhaOQnOw07xfU8spvTWGaPp7HQtMOn4wnHpa6t5ZMrKp1BYn9Oj7WL2QwPnteJh2mV2Rh5Y6xHcb4nxgRZqgyZVUtAZGCLywbb8sbXj,pESNFF9d05ibpmcq1WIG1krbJA0erYTxw1M26VCV1BHHdmGza8Ixu3S9UaOeFAUS8fUsjZzBDzHmDlOPqSBSDzDdbIL5EO0OXj0Fb9EbtTfiJQWgmtH3UFqBrQqrxoUoj8j1TWsENYGCcdL8tJzflwj09fgHSP0btUfIJsxsrvc9YC4374ruMGxlrms4DTICScoPQDdybrN8rFyKskzJ1NzRBgPAfWlJWIoE3Kxfz7auLvTVjVJjnxy3mjAFtD2R,4dQ2JSduHCewZPQg8oHcL1KManvfsVIbXHLFNTDQuBn7OyIeeOubdJc4hOm3I2Jt5c42NpINoSoPKOlkaSSvDZ7RYySxHfP28awiKOUhrFDseL0XXLIFQGRG6K7IMacsDYkxS8kWMvVcQIjs47GKD6ctFAWd1RgsSaonhvJaVNxvs8d2BJBVRGuFdILQzsUiMOiW1Oh0lcDmdSNTaRvbjSg0I8sm5K9UlcmZzTSTzsPkNd6ZWxOfvYzjfv2mbWIN,ESaIIaIbDuPoS7zNFnWjlViqXUEVraaq9NRkRGTPqpSx0mTQO7HrH2RMx0iVZvu6hZjxFGTvn4EkkouViBzbnN8nJr8sar13dxW9sgGQdJGtzsXvqf4TXv8NscpQyOPCVSvd0leXqVAa4IoKJoHin0oAQjOXcCk1yy6kohBLBj5THsnLOf3UccUZjW9w1Xnbndc7fba6Axsklw3cPUzSNngADmlLLPh7DEp7Z5KT9FbEIGzGCr0nywtYRA6DaUg,O,O7UU6E2jVHNLouGiq9TmGrVNDLW7VNOaeEvu9hFzPnEaNBSckrmSX5U4bNR82HxijOmLyE1oRQ61G84Lk4HqjblxRd49DxVLS4fe04x8Oc6EHKXVxHOX3MdNa6OLj37ID51C3jlKLfn70jwjZ1b1iSM2Dq8aMbSQJUGYVbOv8Uxln9yV4fQFq9D0oL875bxCyirUqByPaAizjn6o1NCdqlq8aERCq7toLgaB0IGTs2vdLDPxCO6jTMKOE2PyOpEI,ur5QKoZ20GYLm4blZvpGCv7kiZTfGC0249jjZ7lX242wIwHeGqd7jFrxls8pWQTqyHMMaSdDpSGtFAXsJubweOhyymlSbsx1BWX7mwtlhvNrUOXKEdprC4xsHijU1Q7219HBA0bhOZZrrylCPPwh7OLieM1SawcaCfp4T0iHDzZczVTK4CqGIBpiaHg504GC95ZxvkP2W0iXNSJj6CdVQZijUJF8Nk64dCqVKAMK8tvts8G0iA69EghyLhBt0UCn,kG8xdBNMNrCJuZLL97KxgUktOHeWfgIaSfv6WzsXQ7VGbeI9nqdgfWdXHuifJBe4FQDh7GYjDjVZwL7UxhTm1QytA0net9WTt244VUYDe8lUQaUd0vD5bi8XehwKNWRtR6t45r9NmqNvTdGK5sT4vZvXfsyuVAkoI776vTFH0WhNbXvTmnB5BIPePrl64E0xFA2BBPCVnybWyyvqe9qxffQ9bivPLRziIiV8tkJg1ZNbopnGhJP2SmM4RCg6GXbG,N3SobJOQBQAJvDcSoY7fcjN0JbjzfGGrLCr1WVfMdI4zt5lYXZkYtRYgQxtGimRpDiTcYMdKtzR5xawYr8OywuqfeFvE78NZJOXWWwOQNEniuN2P8OYPb22lAVCvdHz8UUTTYUOzUb73axJhguSX4lrkjZj07r5WrVyA4Rsoa1OJSHD7KYKFhGXQVZVOcZOE7pNNZj3yYhpNv9ggl2XgwA5AFs4L9t1YDyqXTIDSwSQRlER1G5Rbmxob4tqJMGS,z,q4TV6N9pOFNyJ36tDllZBMflqtATcqLjeUQgeQCz5eMqReHP2C60rICQ184tnwBgegVQQepLQWC8jUzptDbLjI1jGaZCziiGjpq0steB31ob5TVX8DaS5j8nPP9llDen9pYqC7aF6TYzzXyhZsxr4Zf1oKEcmETn24RNIVSyDV0ihvdJN2Mgzv6ZnvO89pdAWytnDNkTRWfzF04hMW0PFh8PzYhfPIvJ2SN7WJXWy5MKriVtwGtRbkvpAeSwRtOT,Yoowp5hOLzXaXNM6OsdQ27WMcVIZDWwnkDJIbMF3RPkJnWlKW854OCy8ooERzE4bulHuA9hj8ZmXUU9zRxIFMel6g2NDPFNm9rjSXCy9nEl4HFPc3zMPPmDfFs6ELz9XRc4MHnIXaRl8OW9BJYGYOyvCuR3sYvOOjANRB14WWNH6hEr0AOytmb4zspvTLuuHRQdEfHJUW7jixFkrOHg6x4HBKk6yAiqHCUi4pOH0B9tmRjXwiAUZaVJhr7oybnsQ,1lpNYNdeYGAY4q7wnEVOEiwjRyBxvEGMOTO6W7easOl5RNDdNmw0MLcdA0HUY1ubPmwZ0N6ZWGVi9iBeKwmQ9oYBzU0WJTwl2MrafBRkWe7dEnQcQscxHZk3wwYFkegF'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [5, 6, 7, 9]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [5, 6, 7]
,ok 96 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] Advertiser: session connected Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] Session.startOutputStream(with:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [7, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] Session.startOutputStream(with:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[T,haliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [7, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] Session.startOutputStream(with:) peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [7, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (4664 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server received all data: 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[Th,aliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] VirtualSocket exited RunLoop vsID:10,
[ThaliCore] VirtualSocket.deinit vsID:10 [7, 11, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.di,dSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [7, 12]
[ThaliCore] TCPClient.soc,ketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
cea0mUzzjR3VNl8scOWAQ1AbeIeieyqElX,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'
2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 06:50:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:359AA5C2-7450-4B43-8EBC-C7325FE06F1D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7DC295B6-5886-44D5-B750-7B97D55E9F06", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
,[ThaliCore] Session.deinit peer:4DA74E3F-B06C-42B4-BFB0-D677AD7A44AF
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:50:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7DC295B6-5886-44D5-B750-7B97D55E9F06
2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58918
[ThaliCore] Session.disconnect() peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F
,2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBE9FC79-576C-4F19-B7A7-FF710B850664
[ThaliCore] Browser.startListe,ning
2017-07-24 06:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:50:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
2017-07-24 06:50:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","generation":0}'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C64B7CA2-74CB-48B1-B1C0-43A726C4E62F, (syncValue: tbZ12WjiXpMYyzlp8TcPYq5aebHLxBv1)'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C,4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
2017-07-24 06:50:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE","generation":0}'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
2017-07-24 06:50:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45717B12-6A7B-4A44-B673-96CD3521F8C0","generation":0}'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,4B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,4B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,4B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,4B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C64B7CA2-74CB-48B1-B1C0-43A726C4E62F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C64B7CA2,-74CB-48B1-B1C0-43A726C4E62F error: max retries exceeded
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tbZ12WjiXpMYyzlp8TcPYq5aebHLxBv1","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tbZ12WjiXpMYyzlp8TcPYq5aebHLxBv1', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C64B7CA2-74CB-48B1-B1C0-43A726C4E62F","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:51:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE (syncValue: lIsG5fl,gGmv5oQE6nX6GlLXvgrr6DiYb)'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C583F9D7-EAC2,-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 06:51:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C64B7CA2-74CB-48B1-B1C0-43A726C4E62F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
[ThaliCore] Advertiser: session connected Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,2017-07-24 06:51:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
2017-07-24 06:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
,[ThaliCore] Session.session(_:peer:didChange:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
[ThaliCore] Session.startOutputStream(with:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [7, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 06:51:13 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeS,treams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [7]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58943
2017-07-24 06:51:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lIsG5flgGmv5oQE6nX6GlLXvgrr6DiYb",,"error":null,"portNumber":58943}'
2017-07-24 06:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lIsG5flgGmv5oQE6nX6GlLXvgrr6DiYb', error: 'null', listeningPort: '58943''
Connecting to the localhost:58943
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [7, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:58943
2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-24 06:51:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [7]
,[ThaliCore] Session.session(_:peer:didChange:) peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1B16B594-5A99-4CEB-BFA8-3715D98712DC
,2017-07-24 06:51:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5CA05EEE-49A1-4649-9CDD-C17AD63EEF5F
2017-07-24 06:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58943
[ThaliCore] Session.disconnect() p,eer:C583F9D7-EAC2-4E43-AC34-7A26BB7DB3EE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3720624C-71F8-4A6E-A942-2A1B9013449F
,2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:54214F9C-A37C-499F-AA9C-4C7DED9F7109
[ThaliCore] Browser.startListening
2017-07-24 06:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
2017-07-24 06:51:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45717B12-6A7B-4A44-B673-96CD3521F8C0","generation":0}'
2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45717B12-6A7B-4A44-B673-96CD3521F8C0, (syncValue: XuPoPOQ0Bw3PqUDUUPCfiiRmFCy6PuMB)'
2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45717B12-6A7B-4A44-B673-96CD352,1F8C0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","generation":0}'
2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3720624C-71F8-4A6E-A942-2A1B9013449F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
2017-07-24 06:51:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","generation":0}'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:21 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generatio,n,":0}'
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45717B12-6A7B-4A44-B673-96CD3521F8C0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:51:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XuPoPOQ0Bw3PqUDUUPCfiiRmFCy6PuMB","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XuPoPOQ0Bw3PqUDUUPCfiiRmFCy6PuMB', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:51:26 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"45717B12-6A7B-4A44-B673-96CD3521F8C0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:51:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45717B12-6A7B-4A44-B673-96CD3521F8C0","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 06:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:51:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FEC221C2-D82C-4FE9-8F21-083998DFCE02 (syncValue: fT6veyVXxeeFjMmwQyD44Y5,Ohu3DYVU5)'
2017-07-24 06:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FEC221C2-D82C-4FE9-8F21-08399,8DFCE02:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 ,0,6:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:45717B12-6A7B-4A44-B673-96CD3521F8C0:0
[ThaliCore] BrowserRelay.deinit
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199
[ThaliCore] Advertiser: session connected Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199 state: notConnected -> connecting
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
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
[ThaliCore] Advertiser: session connected Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199
,[ThaliCore] Session.session(_:peer:didChange:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199
[ThaliCore] Session.startOutputStream(with:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [7, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017,-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (13069 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received (20712 bytes):'
,2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 06:51:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,C221C2-D82C-4FE9-8F21-083998DFCE02:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FEC221C2-D82C-4FE9-8F21-083998DFCE02", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fT6veyVXxeeFjMmwQyD44Y5Ohu3DYVU5","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fT6veyVXxeeFjMmwQyD44Y5Ohu3DYVU5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FEC221C2-D82C-4FE9-8F21-083998DFCE02","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 883DCCBF-9953-4452-BB3A-58B0E9E1BBAC (syncValue: E0NuzdaXad85Xw8YQuRDhT03otJyhuum)'
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 06:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FEC221C2-D82C-4FE9-8F21-083998DFCE02:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,15
,[ThaliCore] VirtualSocket.deinit vsID:15 [7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDi,sconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
[ThaliCore] Session.startOutputStream(with:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [7, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (142 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 06:51:35 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58963
2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"E0NuzdaXad85Xw8YQuRDhT03otJyhuum",,"error":null,"portNumber":58963}'
2017-07-24 06:51:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'E0NuzdaXad85Xw8YQuRDhT03otJyhuum', error: 'null', listeningPort: '58963''
,Connecting to the localhost:58963
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
,Connected to the localhost:58963
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 06:51:37 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [7, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [7]
,ok 102 got the same data back
,# teardown
,2017-07-24 06:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3720624C-71F8-4A6E-A942-2A1B9013449F
2017-07-24 06:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58963
[ThaliCore] Session.disconnect() p,eer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:020CD989-5E39-4F44-A1A6-28A20A348E6C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
,[ThaliCore] Session.deinit peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:38 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:111B8154-1B08-4EE3-A5A2-AF7445010199 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3720624C-71F8-4A6E-A942-2A1B9013449F", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:020CD989-5E39-4F44-A1A6-28A20A348E6C
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB743B13-0792-439A-AD85-2D4EC93D9013
[ThaliCore] Browser.startListening
2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:51:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2B8E3465-C24B-4093-8FE5-81825C4AFE05", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2B8E3465-C24B-4093-8FE5-81825C4AF,E,05
2017-07-24 06:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:51:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","generation":0}]'
,2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F45B80A-27AD-4221-BC31-4CA963D9A182:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F45B80A-27AD-4221-BC31-4CA963D9A182", generation: 0)
2017-07-24 06:51:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8F45B80A-27AD-4221-BC31-4CA963D9A182","generation":0}]'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8F45B80A-27AD-4221-BC31-4CA963D9A182","generation":0}'
2017-07-24 06:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B8E3465-C24B-4093-8FE5-81825C4AFE05:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B8E3465-C24B-4093-8FE5-81825C4AFE05", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A5DE92B9-1719-42EA-9D2C-43F8A760B4D1:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A5DE92B9-1719-42EA-9D2C-43F8A760B4D1", generation: 0)
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}]'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A5DE92B9-1719-42EA-9D2C-43F8A760B4D1","generation":0}'
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2B8E3465-C24B-4093-8FE5-8,1825C4AFE05
,2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:43 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:51:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0232622C-9CCF-4335-AF8E-59EE75B4714F
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22BFF144-AE2C-4048-BC70-37573AF608CE", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:22BFF144-AE2C-4048-BC70-37573AF608CE
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:22BFF144-AE2C-4048-BC70-37573AF608CE
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:45 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 06:51:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 06:51:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 06:51:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
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
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9e923966-e445-4258-a306-0db02d11f4a7 error: startListeningNotActive
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"G0MH9EwJTSYdQSKyhmWmZPKwuAFxUJ6c","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9e923966-e445-4258-a306-0db02d11f4a7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9e923966-e445-4258-a306-0db02d11f4a7","peerAvailable":true,"portNumber":null,"recreated":true}'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16A031EF-6F1E-4FB3-B40F-64E71B135CAF
[ThaliCore] Browser.startListening
,2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:51:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-24 06:51:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SpTDce5xS1AJ2qHeTAAq4UnE1n7w9RF9","error":"Illegal peerID","portNumber",:null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 06:51:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:48 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00EB97F7-6A4C-428A-8C09-3E8BD7FADB1D
[ThaliCore] Browser.startListening
2017-07-24 06:51:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:51:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:412aad51-1f5f-4077-9f4a-9224ff17e15c
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:51:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:51:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:51:50 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:59D3765A-2BC9-445D-A1CD-A98041FFB854
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:51:50, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BF2D845E-9BC8-4EFC-A44C-10D4153BC48A
[ThaliCore] Browser.startListening
2017-07-24 06:51:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-24 06:51:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:51:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","generation":0}'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 883DCCBF-9953-4452-BB3A-58B0E9E1BBAC (syncValue: 0aAaS5NRvXJjCR71b1xxqbi1n7AH2Hz7)'
,2017-07-24 06:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
2017-07-24 06:51:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD","generation":0}'
2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:51 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
2017-07-24 06:51:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","generation":0}'
2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:51:51 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59D3765A-2BC9-445D-A1CD-A98041FFB854:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59D3765A-2BC9-445D-A1CD-A98041FFB854", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,83DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,3DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,83DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,3DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,83DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,3DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "883DCCBF-9953-4452-BB3A-58B0E9E1BBAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:883DCCBF,-9953-4452-BB3A-58B0E9E1BBAC error: max retries exceeded
2017-07-24 06:52:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0aAaS5NRvXJjCR71b1xxqbi1n7AH2Hz7","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0aAaS5NRvXJjCR71b1xxqbi1n7AH2Hz7', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:52:01 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 06:52:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"883DCCBF-9953-4452-BB3A-58B0E9E1BBAC","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:52:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:52:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD (syncValue: w06VLYw,znR6I8qTaDMhDMjyxRbP4Sty2)'
2017-07-24 06:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BDBD961E-5DA1,-4B1A-B930-F0E393DCB2BD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 06:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:883DCCBF-9953-4452-BB3A-58B0E9E1BBAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58979
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"w06VLYwznR6I8qTaDMhDMjyxRbP4Sty2",,"error":null,"portNumber":58979}'
2017-07-24 06:52:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'w06VLYwznR6I8qTaDMhDMjyxRbP4Sty2', error: 'null', listeningPort: '58979''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0) found active relay
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hqHQGQ08K68tEFmadq0Y55UMpA9HboXT","error":null,"portNumber":58979}'
,ok 144 No error
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [7, 18]
,ok 145 Ports equal
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD", generation: 0) found active relay
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cwsck6yLHlt4dYVZ6EUOfuAcqSxruB1V","error":null,"portNumber":58979}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-24 06:52:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:59D3765A-2BC9-445D-A1CD-A98041FFB854
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06,:,52:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58979
[ThaliCore] VirtualSocket.closeStr,eams() vsID:18
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Session.disconnect() peer:BDBD961E-5DA1-4B1A-,B930-F0E393DCB2BD:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [7]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.dein,i,t peer:BDBD961E-5DA1-4B1A-B930-F0E393DCB2BD:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-24 06:52:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 06:52:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 06:52:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:07 - DEBUG createNativeListener: 'listening 58982'
ok 149 Should throw
,# teardown
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 58984'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 58987'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 06:52:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 06:52:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'listening 58991'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
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
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 58996'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 59000'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'listening 59004'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 06:52:09 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 59008'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 170 native server is nulled out
ok 171 native server should be cl,osed
ok 172 incoming has been removed
ok 173 Incoming should be done
ok 174 The mux object should be closed
ok 175 The mux stream should be closed
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-07-24 06:52:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'listening 59012'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-24 06:52:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 06:52:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
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
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 06:52:11 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
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
2017-07-24 06:52:11 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-07-24 06:52:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 59064'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-24 06:52:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'listening 59068'
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-24 06:52:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-24 06:52:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-24 06:52:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-24 06:52:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-24 06:52:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:13 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59071'
,ok 196 port must be in range
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59072'
,ok 197 second start should return same port
,# teardown
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 06:52:14 - DEBUG createNativeListener: 'listening 59074'
,2017-07-24 06:52:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 06:52:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-24 06:52:14 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-24 06:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 06:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 200 Passed bogus id
2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 201 Passed good id but bogus port
2017-07-24 06:52:15 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 59076
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolv,e,d registered to native'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:58BABA89-9A63-45D3-9381-F655C03EFBAA
2017-07-24 0,6:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C7DEB75-8BD5-4BC0-BBF2-69A0FFB99CB8
[Tha,l,iCore] Browser.startListening
2017-07-24 06:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","generation":0}'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A69943E-B08F-49FD-A918-3969D49A99E8 (syncValue: ob3NjzV0IUR8keimVowDZ4oF1krpLIP6)'
,2017-07-24 06:52:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","generation":0}'
2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58BABA89-9A63-45D3-9381-F655C03EFBAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
2017-07-24 06:52:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","generation":0}'
2017-07-24 06:52:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:17 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A69943E-B08F-49FD-A918-3969D49A99E8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:52:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ob3NjzV0IUR8keimVowDZ4oF1krpLIP6","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 06:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ob3NjzV0IUR8keimVowDZ4oF1krpLIP6', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 06:52:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 06:52:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1A69943E-B08F-49FD-A918-3969D49A99E8","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 06:52:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 06:52:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 577FB140-91A3-4526-AC67-8110F8393314 (syncValue: YoT3FFAHvEUhSP0XKbh0Ka2,mPcbLA4LQ)'
2017-07-24 06:52:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F,8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1A69943E-B08F-49FD-A918-3969D49A99E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59084
,2017-07-24 06:52:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YoT3FFAHvEUhSP0XKbh0Ka2mPcbLA4LQ","error":null,"portNumber":59084}'
,2017-07-24 06:52:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YoT3FFAHvEUhSP0XKbh0Ka2mPcbLA4LQ', error: 'null', listeningPort: '59084''
,ok 210 should be equal
,2017-07-24 06:52:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A8E8C04-7FDF-475E-B232-F97B78C2F1BC (syncValue: XqW3mOSDpOgSnuWCCFHdWvQFOP72UzCV)'
,2017-07-24 06:52:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A,8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
[ThaliCore] Advertiser: session connected Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59088
2017-07-24 06:52:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XqW3mOSDpOgSnuWCCFHdWvQFOP72UzCV",,"error":null,"portNumber":59088}'
2017-07-24 06:52:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XqW3mOSDpOgSnuWCCFHdWvQFOP72UzCV', error: 'null', listeningPort: '59088''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E
[ThaliCore] Advertiser: session connected Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:52:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:58BABA89-9A63-45D3-9381-F,655C03EFBAA
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:577FB140-91A3-4526-AC67-8110F8393314
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59084
[ThaliCore] Session.disconnect() peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59088
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F5D97DD-7A09-4381-A0F7-D6E67AAE1BC2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0FF912D1-5CA1-4065-9119-570762F25D6E
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:0FF912D1-5CA1-4065-9119-570762F25D6E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "58BABA89-9A63-45D3-9381-F655C03EFBAA", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:52:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 06:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:0FF912D1-5CA1-4065-9119-570762F25D6E
,# Multiple local http requests
,listening on 59090
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ABB6C619-722B-4372-96F0-259A80A2AF24
,2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D0DB2693-5B34-4DA5-BC9F-9E71559,67001
[ThaliCore] Browser.startListening
2017-07-24 06:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:31 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:31 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
2017-07-24 06:52:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","generation":0}'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 577FB140-91A3-4526-AC67-8110F8393314, (syncValue: Sbsoc0ynUE1xoK5aJdWiEtL6vdvuYpdg)'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F83,93314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"2A8E8C04-7FDF-475E-B232-F97B78C2F1BC","generation":0}'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 06:52:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABB6C619-722B-4372-96F0-259A80A2AF24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
2017-07-24 06:52:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 06:52:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A8E8C04-7FDF-475E-B232-F97B78C2F1BC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A8E8C04-7FDF-475E-B232-F97B78C2F1BC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,77FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,77FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F
[ThaliCore] Advertiser: session connected Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,7FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,77FB140-91A3-4526-AC67-8110F8393314", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F
,[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:577FB140-91A3-4526-AC67-8110F8393314:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:577FB140,-91A3-4526-AC67-8110F8393314 error: max retries exceeded
2017-07-24 06:52:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Sbsoc0ynUE1xoK5aJdWiEtL6vdvuYpdg","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:52:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Sbsoc0ynUE1xoK5aJdWiEtL6vdvuYpdg', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:52:42 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:52:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 06:52:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"577FB140-91A3-4526-AC67-8110F8393314","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 06:52:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:52:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:52:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2909281D-1594-4825-9D81-6E148BA659E3 (syncValue: rInixc2,SvnANVuxbQeC3OOoBS4qg4FjG)'
2017-07-24 06:52:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2909281D-1594,-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 06:52:42 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-24 06:52:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] Advertiser: session connected Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:577FB140-91A3-4526-AC67-8110F8393314:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "577FB140-91A3-4526-AC67-8110F8393314", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59109
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rInixc2SvnANVuxbQeC3OOoBS4qg4FjG","error":null,"portNumber":59109}'
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rInixc2SvnANVuxbQeC3OOoBS4qg4FjG', error: 'null', listeningPort: '59109''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8E536049-181F-4A81-B849-449127FF5604 (syncValue: ztPrZVsHJ2xpeYzi6KUwojM2WjHFUrL5)'
,2017-07-24 06:52:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E,536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E536049-181F-4A81-B849-449127FF5604:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59115
,2017-07-24 06:52:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ztPrZVsHJ2xpeYzi6KUwojM2WjHFUrL5","error":null,"portNumber":59115}'
2017-07-24 06:52:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'z,tPrZVsHJ2xpeYzi6KUwojM2WjHFUrL5', error: 'null', listeningPort: '59115''
,ok 220 should be equal
ok 221 should be equal
ok 222 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,06:52:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ABB6C619-722B-4372-96F0-2,59A80A2AF24
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:2909281D-1594-4825-9D81-6E148BA659E3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59109
[ThaliCore] Sessi,on.disconnect() peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:8E536049-181F-4A81-B849-449127FF5604
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59115
,[ThaliCore] Session.disconnect() peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:70C9EA24-659A-4E25-B83C-F5CC88A1521F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ABB6C619-722B-4372-96F0-259A80A2AF24", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
,[ThaliCore] Session.deinit peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:52:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:88AD5FE9-BEA1-4CBA-B247-79E9A6293452
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'listening 59119'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7A044E69-D1AC-464E-BCD4-5D242BEBB436
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
ok 228 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,# teardown
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:52:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:51 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:51 - DEBUG makeIntoCloseAllServer: 'closeAll called, on server'
ok 230 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'listening 59121'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "05F5839E-183E-4B2D-844D-72C7E6F0E6FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:05F5839E-183E-4B2D-844D-72C7E6F0E6FA
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "05F5839E-183E-4B2D-844D-72C7E6F0E6FA", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:05F5839E-183E-4B2D-844D-72C7E6F0E6FA
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:05F5839E-183E-4B2D-844D-72C7E6F0E6FA
,[ThaliCore] Advertiser.stopAdvertising() peerID:05F5839E-183E-4B2D-844D-72C7E6F0E6FA
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
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
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'listening 59124'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 236 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 06:52:52 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 59125'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D2F17AC6-A4CE-473E-800C-414332F6955D
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71F7ABEE-7E4B-4164-9E80-F5B19022330F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:71F7ABEE-7E4B-4164-9E80-F5B19022330F
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:71F7ABEE-7E4B-4164-9E80-F5B19022330F
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 59128'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:56A6AF12-28B6-4708-AF8D-1D31EAEC3D83
,[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
[ThaliCore] AdvertiserManager,.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DD7F38D-DCCC-4787-8188-C538D8CE4B46", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2DD7F38D-DCCC-4787-8188-C538D8CE4B46
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,# teardown
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2DD7F38D-DCCC-4787-8188-C538D8CE4B46
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 06:52:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:54 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'listening 59130'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E0ABFEE4-DABC-4CD6-893B-A041D7F54524
[ThaliCore] Browser.startListening
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CDEA8553-5FF2-4EAB-B75C-5558BDD82047", genera,tion: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CDEA8553-5FF2-4EAB-B75C-5558BDD82047
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CDEA8553-5FF2-4EAB-B75C-5558BDD82047
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:52:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:52:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
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
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 06:52:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:52:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
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
2017-07-24 06:52:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 06:52:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 06:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:52:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 06:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59133'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7E0C0EB5-E83F-4A7E-80CA-59A0A963D04C
[ThaliCore] Browser.st,artListening
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive matches
,ok 267 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59134'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "73F8C39F-543B-4381-AEEC-D7D4B8866D1F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:73F8C39F-543B-4381-AEEC-D7D4B8866D1F
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:73F8C39F-543B-4381-AEEC-D7D4B8866D1F
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59136'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:00 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'listening 59137'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA890B18-1299-419F-B263-C57958BBCE3F
[ThaliCore] Browser.st,artListening
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:00 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35007D94-7682-4602-947D-7A22EA1AB0AF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,35007D94-7682-4602-947D-7A22EA1AB0AF
2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:53:00 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:00 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:53:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:35007D94-7682-4602-947D-7A22EA1AB0AF
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 277 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-24 06:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-24 06:53:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'listening 59139'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44A36F3F-1BFB-41FA-8605-63912AF617AE
[ThaliCore] Browser.st,artListening
2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:53:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}]'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","generation":0}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2909281D-1594-4825-9D81-6E148BA659E3 (syncValue: ospqL34IpsbRgXfzySxWGyDApCIxWuAL)'
,2017-07-24 06:53:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0,
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57D5CC84-0578-4F84-9A1C-FCC81840B6BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57D5CC84-0578-4F84-9A1C-FCC81840B6BB", generation: 0)
2017-07-24 06:53:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","generation":0}]'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","generation":0}'
,2017-07-24 06:53:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 06:53:06 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,09281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,909281D-1594-4825-9D81-6E148BA659E3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6
[ThaliCore] Advertiser: session connected Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
[ThaliCore] Advertiser: session connected Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,909281D-1594-4825-9D81-6E148BA659E3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6
[ThaliCore] Session.startOutputStream(with:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [7, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,2017-07-24 06:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
,2017-07-24 06:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:53:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
[ThaliCore] Session.startOutputStream(with:) peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [7, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,09281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,909281D-1594-4825-9D81-6E148BA659E3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E536049-181F-4A81-B849-449127FF5604:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E536049-181F-4A81-B849-449127FF5604", generation: 0)
,2017-07-24 06:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}]'
,2017-07-24 06:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","generation":0}'
,2017-07-24 06:53:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:53:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8E536049-181F-4A81-B849-449127FF5604","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2909281D-1594-4825-9D81-6E148BA659E3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2909281D-1594-4825-9D81-6E148BA659E3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2909281D,-1594-4825-9D81-6E148BA659E3 error: max retries exceeded
2017-07-24 06:53:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ospqL34IpsbRgXfzySxWGyDApCIxWuAL","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 06:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ospqL34IpsbRgXfzySxWGyDApCIxWuAL', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 06:53:15 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 06:53:15 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 06:53:15 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 06:53:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 06:53:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"2909281D-1594-4825-9D81-6E148BA659E3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 06:53:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 06:53:15 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 52C68463-0618-4ED7-A9C9-4CE393CD01D3 (syncValue: ADx9v4Hy9KpQZ0Yj2rzNp0IsqTB629Ev)'
2017-07-24 06:53:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4,CE393CD01D3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2909281D-1594-4825-9D81-6E148BA659E3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59154
2017-07-24 06:53:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ADx9v4Hy9KpQZ0Yj2rzNp0IsqTB629Ev",,"error":null,"portNumber":59154}'
2017-07-24 06:53:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ADx9v4Hy9KpQZ0Yj2rzNp0IsqTB629Ev', error: 'null', listeningPort: '59154''
,2017-07-24 06:53:18 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [7, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:19 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:19 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-07-24 06:53:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDe,scription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discove,ryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:19, - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [7, 20, 21]
,[ThaliCore] BrowserManager.disconnect peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59154
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:20 [7, 21]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserR,elay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] Session.disconnect() peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:21 [7]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 06:53:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B6DCCC8-5ED7-486C-B315-0E5E57E3E1A6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8AAB39B9-B55E-4DBD-9D60-BFB4E7F06D00", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
,[ThaliCore] Session.deinit peer:F4820D67-FF22-4973-BA78-9D6070EDB5AC
[ThaliCore] AdvertiserRelay.deinit
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:20 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 06:53:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 06:53:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 06:53:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 06:53:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-24 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2909281D-1594-4825-9D81-6E148BA659E3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:53:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 06:53:22 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57D5CC84-0578-4F84-9A1C-FCC81840B6BB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
ok 291 error should be null
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
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'listening 59156'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 06:53:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59157'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E22505E3-3531-495D-83A3-0A94C3D765B9
[ThaliCore] Browser.st,artListening
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 304 error should be null
ok 305 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:23 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59158'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "176A130A-28C9-444D-8DA8-A52948E885E5", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:176A130A-28C9-444D-8DA8-A52948E885E5
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "176A130A-28C9-444D-8DA8-A52948E885E5", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:176A130A-28C9-444D-8DA8-A52948E885E5
20,17-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:176A130A-28C9-444D-8DA8-A52948E885E5
[ThaliCore] Advertiser.stopAdvertising() peerID:176A130A-28C9-444D-8DA8-A52948E885E5
2017-07-24 06:53:23 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'listening 59161'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 06:53:24 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
,ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'listening 59162'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 06:53:24 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 06:53:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f3aab4c0-72fb-4724-b708-f4de1f74a744","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 342 should be calle,d once
ok 343 should not have been called more than once
,# teardown
,2017-07-24 06:53:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f3aab4c0-72fb-4724-b708-f4de1f74a744","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40c747f8-ef0c-4977-b216-4174cd94b5f2","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
,ok 352 peer should be available
ok 353 cache contains native peer
2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40c747f8-ef0c-4977-b216-4174cd94b5f2","connectionType":"MPCF","peerAvailable":,false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7aeebf6-fa27-4a94-a3ad-bfdc9b1b0dad","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 360 peer should be available
,ok 361 cache contains wifi peer
,2017-07-24 06:53:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7aeebf6-fa27-4a94-a3ad-bfdc9b1b0dad","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"53a62a4f-19f2-474e-8b5b-e6f4ad42c9a6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 367 first peer is a,vailable
2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"848ccd4e-c65a-4d63-9a05-df4b702c067b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 second peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"53a62a4f-19f2-474e-8b5b-e6f4ad42c9a6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"848ccd4e-c65a-4d63-9a05-df4b702c067b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"511a8ff0-4c9e-428e-b838-72bc7f87cbc6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 374 peer is available
,# teardown
,2017-07-24 06:53:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"511a8ff0-4c9e-428e-b838-72bc7f87cbc6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 06:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 06:53:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fc55388-b2b1-4a97-b504-ed275f675c10","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be available
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fc55388-b2b1-4a97-b504-ed275f675c10","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be available
ok 386 should store correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8fc55388-b2b1-4a97-b504-ed275f675c10","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'listening 59163'
2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba512f4f-8472-489d-90fe-a1adcff30f31","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba512f4f-8472-489d-90fe-a1adcff30f31","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 392 discovered corr,ect peer
ok 393 got correct generation
,# teardown
,2017-07-24 06:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ba512f4f-8472-489d-90fe-a1adcff30f31","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 394 error should be null
ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 59164'
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c9198102-a7e5-4b21-ac25-f35e0c340d87","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered available peer
ok 398 peer is available
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c9198102-a7e5-4b21-ac25-f35e0c340d87","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 399 error should be null
ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d429a7fc-2d34-41f7-ad05-602f4a31a863","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d429a7fc-2d34-41f7-ad05-602f4a31a863","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 403 peer should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 59165'
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0c774601-78a4-4840-a84b-d0cba794e258","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0355dd97-cdf4-4653-b219-3621b9a003e5","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0355dd97-cdf4-,4653-b219-3621b9a003e5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 410 peer became unavailable
ok 411 it was wifi peer
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0355dd97-cdf4-4653-b219-3621b9a003e5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 412 we found peer ag,ain
ok 413 it was wifi peer
2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0355dd97-cdf4-4653-b219-3621b9a003e5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAd,dressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
,# teardown
,2017-07-24 06:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0c774601-78a4-4840-a84b-d0cba794e258","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 06:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 06:53:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 59166'
2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d83620b7-0833-4ee3-8f54-4aa306bb05f9","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c42767c9-047e-43f9-82df-ad5475b22ccb","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d83620b7-0833-4ee3-8f54-4aa306bb05f9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 424 pee,r became unavailable
2017-07-24 06:53:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c42767c9-047e-43f9-82df-ad5475b22ccb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 06:53:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
,ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 06:53:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec9368a7-8e92-4a55-8980-13d042c2aa2b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec9368a7-8e92-4a55-8980-13d042c2aa2b","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 436 address has not been changed
2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec9368a7-8e92-4a55-8980-13d042c2aa2b","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 437 new port handled correctly
2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec9368a7-8e92-4a55-8980-13d042c2aa2b","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled correctly
2017-07-24 06:53:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ec9368a7-8e92-4a55-8980-13d042c2aa2b","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 06:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-24 06:53:32 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
,ok 461 the same hostAddress
,ok 462 the same portNumber
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 59167'
2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e9a0bbf3-795f-4e82-8bff-240b5d8905bd","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 472 Got specific error message
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e9a0bbf3-795f-4e82-8bff-240b5d8905bd","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-,07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'listening 59168'
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"917deffe-5fce-4a84-a436-d89ef4d51a74","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:917deffe-5fce-4a84-a436-d89ef4d51a74
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 06:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"917deffe-5fce-4a84-a436-d89ef4d51a74","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 06:53:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 06:53:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 06:53:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'listening 59169'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:81AA1891-BF27-492C-8CCB-887C603B38F4
[ThaliCore] Browser.startListening
2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b863648c-1e45-4f85-ada1-1a814c6d7b90","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0a2ed6c4-4732-4c18-ad11-6fa71e56b151","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b863648c-1e45-4f85-ada1-1a814c6d7b90","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0a2ed6c4-4732-4c18-ad11-6fa71e56b151","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:53:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'listening 59170'
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d4cde4e-81c2-406e-bf67-5bcbe0fd2a4e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 510 1
,ok 511 2
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6cffb66c-5e88-4b19-9d12-23b99e7baf2a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1d4cde4e-81c2-406e-bf67-5bcbe0fd2a4e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:53:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6cffb66c-5e88-4b19-9d12-23b99e7baf2a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 06:53:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:53:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:53:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 06:53:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'listening 59171'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3,E61402067D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EF040FDE-0D6B-4D8D-A867-F3E61402067D
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 520 error should be null
,ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26C05849-3F22-49F2-A0F7-79E37AD78BE9
[ThaliCore] Browser.startListening
2017-07-24 06:53:38 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:53:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 52C68463-0618-4ED7-A9C9-4CE393CD01D3 (syncValue: 0)'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}]'
2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","generation":0}'
,2017-07-24 06:53:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 06:53:38 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
2017-07-24 06:53:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EF040FDE-0D6B-4D8D-A867-F3E61402067D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
2017-07-24 06:53:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}]'
2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","generation":0}'
,2017-07-24 06:53:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 06:53:39 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,2C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52C68463-0618-4ED7-A9C9-4CE393CD01D3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 06:53:40 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 1)'
,2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52C68463-0618-4ED7-A9C9-4CE393CD01D3","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
[ThaliCore] Advertiser: session connected Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59178
2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":59178}'
,2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2E94013A-F1F3-45ED-A4A4-58C18682083B (syncValue: 2)'
,2017-07-24 06:53:43 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Advertiser: session connected Peer(uuid: "EF040FDE-0D6B-4D8D-A867-F3E61402067D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
[ThaliCore] Session.startOutputStream(with:) peer:DDBEB3AF-D6A6-4E36-B2B5-CFA5B4CEB06E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [7, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [7, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 06:53:44 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:53:44 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] Session.startOutputStream(with:) peer:3144DD4B-A2E1-4D8B-85AC-C866464CD67D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [7, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59184
,2017-07-24 06:53:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":59184}'
,[ThaliCore] BrowserManager.disconnect peer:52C68463-0618-4ED7-A9C9-4CE393CD01D3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [7, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:53:47 - DEBUG testUtils: 'Got response data'
2017-07-24 06:53:47 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EF040FDE-0D6B-4D8D-A867-F3E61402067D
,2017-07-24 06:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 06:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:53:51 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,O,ptional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.d,idSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:fa,lse socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore], AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStrea,msHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:22, [7, 23, 24, 25]
[ThaliCore] VirtualSocket.deinit vsID:24 [7, 23, 25]
,ok 525 error should be null
,ok 526 error should be null
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:59184
[ThaliCore] Session.disconnect() peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2E94013A-F1F3-45ED-A4A4-58C18682083B", generation: 0)
2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected",,"portNumber":null}'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2E94013A-F1F3-45ED-A4A4-58C18682083B","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:53:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:2E94013A-F1F3-45ED-A4A4-58C18682083B:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[Th,aliCore] VirtualSocket.deinit vsID:23 [7, 25]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconn,ectHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 06:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
ok 531 getConnectionType
ok 532 getActionType
ok 533 getActionState
ok 534 getPskIdentity
ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
ok 537 after start
2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 06:53:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 clean kill
ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
ok 544 agent's destroy should be called
ok 545 agent's destroy should not be called again
ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
ok 548 Entry exists
ok 549 Size must be 1
ok 550 Entry counter must be 2
ok 551 Entry exists
ok 552 Size must be 2
ok 553 Entry counter must be 1
ok 554 Entry exists
ok 555 Size must be 3
ok 556 Entry counter must be 2
ok 557 Entry exists
ok 558 Size must be 4
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
ok 575 Size should be MAXSIZE
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
ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
,ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
,ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
ok 593 good enqueue
,ok 594 Identity should match
,2017-07-24 06:54:05 - DEBUG testUtils: 'Got response data'
,2017-07-24 06:54:05 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-24 06:54:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 607 good enqueue
,ok 608 queue is not empty
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
,ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
ok 625 2nd good enqueue
,ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 06:54:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 631 Got right error
ok 632 Start should not be called
ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:08 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 634 Got right error
ok 635 Start should not be called
ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 637 Got null
2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 638 is an agent
2017-07-24 06:54:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 647 should have gotten null
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 648 Should have stopped nicely
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
ok 649 Still looking for null
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 06:54:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 664 is an agent
ok 665 First does, not throw
2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 666 is an agent
ok 667 Second does not throw
2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-24 06:54:10 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-24 06:54:11 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
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
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-24 06:54:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-24 06:54:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-24 06:54:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-24 06:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
,ok 689 Start after killed
,# teardown
,2017-07-24 06:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-24 06:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-24 06:54:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 695 must return null after successful call
,# teardown
,2017-07-24 06:54:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 06:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-24 06:54:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 707 should be equal
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
# teardown
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
,2017-07-24 06:54:28 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
,2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 06:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-07-24 06:54:30 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-24 06:54:30 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 06:54:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-07-24 06:54:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-24 06:54:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-24 06:54:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-24 06:54:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-24 06:54:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 06:54:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:35 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 06:54:35 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
,# teardown
,2017-07-24 06:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 06:54:38 - WARN thaliNotificationClient: 'peer is not available'
2017-07-24 06:54:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-24 06:54:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 06:54:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
,ok 769 peer state should be RESOLVED
,# teardown
,2017-07-24 06:54:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 06:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-07-24 06:54:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
ok 777 connectionType must match
,# teardown
,2017-07-24 06:54:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-24 06:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-24 06:54:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 06:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 06:54:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-24 06:54:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 06:54:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 06:54:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-24 06:54:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
ok 803 should be 204
# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
# teardown
,2017-07-24 06:54:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
2017-07-24 06:54:49 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
ok 812 first action kill called
ok 813 second action kill called
ok 814 first cleared dictionary
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
,2017-07-24 06:54:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-24 06:54:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-24 06:54:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-24 06:54:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:54:51 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-24 06:54:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-24 06:54:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-24 06:54:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-24 06:54:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-24 06:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-24 06:54:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-24 06:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-24 06:54:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-24 06:54:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-24 06:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-24 06:54:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:54:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:54:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
,ok 851 All tests passed!
,# teardown
,2017-07-24 06:55:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-24 06:55:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-24 06:55:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-24 06:55:05 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-24 06:55:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 06:55:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-24 06:55:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-24 06:55:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-24 06:55:08 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-24 06:55:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 06:55:10 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
ok 859 Error should be timed out
,# teardown
,2017-07-24 06:55:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-24 06:55:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
ok 863 same localDbName
ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-24 06:55:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'listening 59311'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:97151C4D-7F1C-4629-935C-17A356F2D7DA
,[ThaliCore] Browser.startListening
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2C25BD08-82E6-4993-AE40-B3DCC8B04381
,2017-07-24 06:55:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
2017-07-24 06:55:15 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","generation":0}]'
2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","generation":0}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 99E26CE2-0BAD-4BFD-95A2-9934C3008397 (syncValue: 3)'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25BD08-82E6-4993-AE40-B3DCC8B04381:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}]'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","generation":0}'
,2017-07-24 06:55:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Advertiser: session connected Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [7, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "99E26CE2-0BAD-4BFD-95A2-9934C3008397", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59316
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":59316}'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00404456-957A-4F5F-9043-36855CD19826 (syncValue: 4)'
,2017-07-24 06:55:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00,404456-957A-4F5F-9043-36855CD19826", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [7, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [7, 25, 27]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [7, 25, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Advertiser: session connected Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8DF661A8-4296-4094-A555-B2F18A543288 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] TCPLis,tener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [7, 25, 28]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [7, 25, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,0 [7, 25, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:peer:didChange:) peer:00404456-957A-4F5F-9043-36855CD19826:0 state: notConnected -> connecting
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-24 06:55:19 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [7, 25, 28, 29, 30, 31]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [7, 25, 28, 29, 30, 31, 32]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [7, 25, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [7, 25, 28, 29, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [7, 25, 29, 30, 31, 32, 33, 34]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [7, 25, 29, 30, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [7, 25, 29, 30, 31, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] Session.startOutputStream(with:) peer:D6EAF055-2C60-4762-A755-7A84207314F0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [7, 25, 29, 30, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [7, 25, 29, 30, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [7, 25, 29, 30, 31, 32, 33, 34, 35, 36, 38]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:99E26CE2-0BAD-4BFD-95A2-9934C3008397:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:00404456-957A-4F5F-9043-36855CD19826:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59332
2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":59332}'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 5)'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":59178}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DF661A8-4296-4094-A555-B2F18A543288 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 40]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 41]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 42, 43]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOu,tputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 6)'
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":59178}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:55:21 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,8 [7, 25, 29, 30, 31, 32, 33, 34, 35, 38, 43, 44, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 7)'
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":59178}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endE,ncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [7, 25, 29,, 30, 31, 33, 34, 35, 38, 43, 44, 46, 47, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [7, 25, 29, 30, 31, 34, 35, 38, 43, 44, 46, 47, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] Vir,tualSocket.init(inputStream:outputStream:) vsID:49 [7, 25, 29, 30, 31, 34, 35, 38, 43, 44, 46, 47, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:34 [7, 25, 29, 3,0, 31, 35, 38, 43, 44, 46, 47, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:49 [7, 25, 29, 30, 31, 35, 38, 43, 44, 46, 47, 48]
,2017-07-24 06:55:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [7, 25, 29, 30, 31, 35, 38, 43, 44, 46, 47, 48, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [7, 25, 30, 31, 35, 38, 43, 44, 46, 47, 48, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:31 [7, 25, 30, 35, 38, 43, 44, 46, 47, 48, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:35 [7, 25, 30, 38, 43, 44, 46, 47, 48, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:38 [7, 25, 30, 43, 44, 46, 47, 48, 50]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Session.startOutputStream(with:) peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [7, 25, 30, 43, 44, 46, 47, 48, 50, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [7, 25, 30, 43, 44, 46, 47, 48, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [7, 25, 30, 44, 46, 47, 48, 50, 51, 52]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [7, 25, 30, 44, 47, 48, 50, 51, 52]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [7, 25, 30, 44, 47, 48, 51, 52]
,2017-07-24 06:55:22 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-24 06:55:22 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [7, 25, 30, 44, 47, 48, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [7, 25, 30, 47, 48, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [7, 25, 30, 48, 51]
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [7, 25, 30, 51]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSoc,ket.deinit vsID:51 [7, 25, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2C25BD08-82E6-4993-AE40-B3DCC8B04381
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"99E26CE2-0BAD-4BFD-95A2-9934C3008397","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:55:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:55:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 865 passed
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:00404456-957A-4F5F-9043-36855CD19826:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59332
[ThaliCore] Session.disconnect() peer:00404456-957A-4F5F-9043-36855CD19826:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "00404456-957A-4F5F-9043-36855CD19826", generation: 0)
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00404456-957A-4F5F-9043-36855CD19826","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:00404456-957A-4F5F-9043-36855CD19826:0
[ThaliCore] BrowserRelay.deinit
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'listening 59346'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD222EF8-2D21-4EA0-9E70-70AEBA8F1FEB
[ThaliCore] Browser.startListening
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E70E9642-D542-4465-BF89-DFBB13C20E5E
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 8)'
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":59178}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [7, 25, 30, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 06:55:33 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 9)'
2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
2017-07-24 06:55:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":59178}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [7, 25, 30, 53, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[Th,aliCore] VirtualSocket.deinit vsID:54 [7, 25, 30, 53]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocke,tDisconnectHandler
,2017-07-24 06:55:33 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 10)'
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) found active relay
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":59178}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [7, 25, 30, 53, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[Th,aliCore] VirtualSocket.deinit vsID:55 [7, 25, 30, 53]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocke,tDisconnectHandler
,2017-07-24 06:55:34 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E70E9642-D542-4465-BF89-DFBB13C20E5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
2017-07-24 06:55:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","generation":0}]'
2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 773BB6AC-864D-4771-BE0C-DA3F1B91DBAC (syncValue: 11)'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","generation":0}]'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","generation":0}'
,2017-07-24 06:55:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 06:55:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Advertiser: session connected Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
,[ThaliCore] Session.session(_:peer:didChange:) peer:D6EAF055-2C60-4762-A755-7A84207314F0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2C25BD08-82E6-4993-AE40-B3DCC8B04381", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8DF661A8-4296-4094-A555-B2F18A543288
,[ThaliCore] Session.deinit peer:8DF661A8-4296-4094-A555-B2F18A543288
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:59178
,[ThaliCore] Session.disconnect() peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) relay removed
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}]'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","generation":0}'
,2017-07-24 06:55:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 06:55:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 06:55:36 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "773BB6AC-864D-4771-BE0C-DA3F1B91DBAC", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59352
,2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":59352}'
,2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1 (syncValue: 12)'
,2017-07-24 06:55:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0B,A7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [7, 25, 30, 53, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [7, 25, 30, 53]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:773BB6AC-864D-4771-BE0C-DA3F1B91DBAC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [7, 25, 30, 53, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:37 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:37 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 866 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:57 [7, 25, 30, 53]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Session.startOutputStream(with:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [7, 25, 30, 53, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] Session.startOutputStream(with:) peer:5EAC8A52-9DEF-456D-B005-BD895182E631
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [7, 25, 30, 53, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [7, 25, 30, 53, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false,
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:59 [7, 25, 30, 53]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59359
2017-07-24 06:55:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":null,"portNumber":59359}'
,2017-07-24 06:55:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 00C1C796-5CC2-40AC-8AE1-B6E3EEA96871 (syncValue: 13)'
,2017-07-24 06:55:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "00C1C796-5CC2-40AC-8AE1-B6E3EEA96871", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 06:55:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 06:55:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:41 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-24 06:55:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 06:55:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"00C1C796-5CC2-40AC-8AE1-B6E3EEA96871","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] TCPListener.socket(_:didAcceptNe,wSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] BrowserManager.disconnect peer:00C1C796-5CC2-40AC-8AE1-B6E3EEA96871
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [7, 25, 30, 53, 60]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:60 [7, 25, 30, 53]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [7, 25, 30, 53, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 06:55:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-24 06:55:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 867 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:61 [7, 25, 30, 53]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Advertiser: session connected Peer(uuid: "E70E9642-D542-4465-BF89-DFBB13C20E5E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Session.startOutputStream(with:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,2 [7, 25, 30, 53, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,62
[ThaliCore] VirtualSocket.deinit vsID:62 [7, 25, 30, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserR,elay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
[ThaliCore] Session.startOutputStream(with:) peer:06C20BBF-824D-441C-A61E-A8878A7135B6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [7, 25, 30, 53, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [7, 25, 30, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E70E9642-D542-4465-BF89-DFBB13C20E5E
2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
,2017-07-24 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"773BB6AC-864D-4771-BE0C-DA3F1B91DBAC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 06:55:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0BA7E99F-088C-49E5-A4CA-BD42E53A0ED1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:55:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 06:55:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopp,e,d state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:55:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
2017-07-24 06:55:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:55:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
# teardown
,# setup
,# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,ok 879 should be equal
,ok 880 should be equal
ok 881 should throw
,# teardown
,# setup
,# Test TransientState
,ok 882 should throw
,ok 883 should throw
ok 884 should be equal
ok 885 should be equal
ok 886 should be equal
ok 887 should be equal
ok 888 (unnamed assert)
ok 889 (unnamed assert)
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
,2017-07-24 06:55:54 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:55:57 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 925 verify failed
ok 926 constructor called once
,ok 927 constructor called with right args
,ok 928 match start arg
,ok 929 start called once
,ok 930 stop called once
,ok 931 stop after start
,# teardown
,# setup
,# More than maximum peers, make sure we only send maximum allowed
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 932 verify failed
,ok 933 constructor called once
,ok 934 constructor called with right args
,ok 935 match start arg
ok 936 start called once
,ok 937 stop called once
,ok 938 stop after start
,# teardown
,# setup
,# two peers with empty DB, update the doc
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:58 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 939 verify failed
ok 940 constructor called once
ok 941 constructor called with right args
ok 942 last start before stop
ok 943 empty first start
ok 944 full second start
ok 945 only 2 timers
# teardown
,# setup
,# add doc and make sure tokens refresh when they expire
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,2017-07-24 06:55:59 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:56:00 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 958 back to null
,2017-07-24 06:56:00 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:56:01 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 966 verify failed
ok 967 constructor called once
ok 968 constructor called with right args
,ok 969 (unnamed assert)
,# teardown
,# setup
,# two different starts in a row
,2017-07-24 06:56:02 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 970 verify failed
,ok 971 constructor called once
,ok 972 constructor called with right args
,ok 973 (unnamed assert)
,ok 974 (unnamed assert)
,# teardown
,# setup
,# two stops and a start and two stops
,2017-07-24 06:56:02 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
,ok 975 verify failed
,ok 976 constructor called once
,ok 977 constructor called with right args
,ok 978 start before stop
,# teardown
,# setup
,# we properly enqueue requests so no then needed
,2017-07-24 06:56:03 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,2017-07-24 06:56:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 06:56:04 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 985 Got right error
# teardown
,2017-07-24 06:56:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server accepts & closes connection
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 986 Got socket hang up
# teardown
,2017-07-24 06:56:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-24 06:56:05 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 987 Got 500 as expected
# teardown
,2017-07-24 06:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - create new seq doc
,ok 988 should be equal
,ok 989 revs are equal
,# teardown
,2017-07-24 06:56:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - doc exists, need to get rev and update
,ok 990 should be equal
,ok 991 revs are equal
,# teardown
,2017-07-24 06:56:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - update seq three times
,ok 992 should be equal
,ok 993 revs are equal
,ok 994 should be equal
ok 995 revs are equal
,ok 996 should be equal
ok 997 revs are equal
,# teardown
,2017-07-24 06:56:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/D,C7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/DC7A9036-,8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-24 06:56:11 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
ok 998 Our rev is old so we should fail
,# teardown
,2017-07-24 06:56:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 999 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/DC7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/D,C7A9036-8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/DC7A9036-,8872-4F00-8247-17C427D49B29/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,# teardown
,2017-07-24 06:56:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - stop after get but before put fails right
,2017-07-24 06:56:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,ok 1000 stop caused us to fail
,ok 1001 We specifically failed on a stop before put
,# teardown
,2017-07-24 06:56:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - fail if stop is called
,ok 1002 failed due to stop
,ok 1003 failed due to stop
,# teardown
,2017-07-24 06:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - set seq for first time
,ok 1004 should be equal
,# teardown
,2017-07-24 06:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - Fail on bad seq value
,2017-07-24 06:56:20 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 1005 Expected bad seq error
,# teardown
,2017-07-24 06:56:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1006 Different promises
,ok 1007 Timer was cancelled
,ok 1008 should be equal
,# teardown
,2017-07-24 06:56:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we wait for blocked update
,ok 1009 One go and one blocked
,ok 1010 All blocked
,ok 1011 Still blocked
,ok 1012 should be equal
,# teardown
,2017-07-24 06:56:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we wait long enough
,ok 1013 We waited long enough
,ok 1014 should be equal
,# teardown
,2017-07-24 06:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - test that we pick up new sequences while we wait
,ok 1015 Should have gotten same timer promise
ok 1016 Still same timer promise
,ok 1017 We waited long enough
,ok 1018 should be equal
,# teardown
,2017-07-24 06:56:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-24 06:56:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:56:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:56:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1019 expressPouchDB was called once
ok 1020 expressPouchDB was called with 2 arguments
ok 1021 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1022 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1023 PouchDB was called once
,ok 1024 PouchDB was called with 1 arguments
,ok 1025 PouchDB was called with 'dbName' as 1-st argument
,ok 1026 ThaliSendNotificationBasedOnReplication was called once
ok 1027 ThaliSendNotificationBasedOnReplication was called with 4 arguments
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:33 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'listening 59433'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:413C8809-AB23-4BF3-9ECA-FEAFB11EEF53
[ThaliCore] Browser.startListening
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EF051AAD-3A0F-4FC3-B5CD-73F83082F79A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EF051AAD-3A0F-4FC3-B5CD-73F83082F79A
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:56:33 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1044 ThaliMobile.start was called once
,ok 1045 ThaliMobile.start was called with 3 arguments
ok 1046 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
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
,2017-07-24 06:56:33 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EF051AAD-3A0F-4FC3-B5CD-73F83082F79A
,2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:56:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1059 ThaliMobile.stop was called once
ok 1060 ThaliMobile.stop was called with 0 arguments
,ok 1061 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1062 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1063 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1064 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 06:56:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-24 06:56:33 - DEBUG thaliManager: 'creating express pouchdb instance'
,ok 1065 expressPouchDB was called once
,ok 1066 expressPouchDB was called with 2 arguments
,ok 1067 expressPouchDB was called with 'PouchDB' as 1-st argument
,ok 1068 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 1069 PouchDB was called once
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 59435'
2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CDA157A8-B5C1-4591-AED2-D99B295FAB5F
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD30C170-324D-4358-9269-25FD7893D042", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BD30C170-324D-4358-9269-25FD7893D042
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1090 ThaliMobile.start was called once
ok 1091 ThaliMobile.start was called with 3 arguments
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BD30C170-324D-4358-9269-25FD7893D042
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 06:56:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1105 ThaliMobile.stop was called once
,ok 1106 ThaliMobile.stop was called with 0 arguments
,ok 1107 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1108 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1109 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1110 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 59437'
2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:510F27EB-B91D-463D-B183-D8AA75827981
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "242608BC-AC6D-4B2F-BBC8-05E01AA47E37", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:242608BC-AC6D-4B2F-BBC8-05E01AA47E37
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:242608BC-AC6D-4B2F-BBC8-05E01AA47E37
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 59439'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0E590144-AF4A-4700-93FB-FE7067D31B9C
[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B412D833-C092-4535-89C7-216FE0560EA0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B412D833-C092-4535-89C7-216FE0560EA0
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B412D833-C092-4535-89C7-216FE0560EA0
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2017-07-24 06:56:34 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'listening 59441'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:135D45E4-39F5-4E09-A0FF-F162B6C9DA5F
,[ThaliCore] Browser.startListening
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3150E6DE-07E9-4B6A-A473-DD0745FF0BF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3150E6DE-07E9-4B6A-A473-DD0745FF0BF7
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 06:56:34 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,ok 1111 ThaliMobile.start was called once
ok 1112 ThaliMobile.start was called with 3 arguments
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
,2017-07-24 06:56:34 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3150E6DE-07E9-4B6A-A473-DD0745FF0BF7
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 06:56:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 06:56:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 06:56:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 06:56:37 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-24 06:,56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-24 06:56:37 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
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
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
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
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
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
2017-07-24 06:56:37 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
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
2017-07-24 06:56:37 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-24 06:56:37 - DEBUG CoordinatedT,haliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
