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
,(lldb) command source -s 0 '/tmp/1487E331-839F-4D02-BFBF-AAA7C8C5BF26/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1487E331-839F-4D02-BFBF-AAA7C8C5BF26/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851520d16b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56966"
,(lldb)     command script import "/tmp/1487E331-839F-4D02-BFBF-AAA7C8C5BF26/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AAAEF595-D810-4B48-B5FE-70D995F8665D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AAAEF595-D810-4B48-B5FE-70D995F8665D
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E15AE86A-8682-48D0-B07E-AAE0F7F48BE0
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CA3BDD6D-,5F52-4E8D-9473-BCF7BC532F71
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "55AB34FC-C679-4FF2-A62B-3FA63CCF185B", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:55AB34FC-C679-4FF2-A62B-3FA63CCF185B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:55AB34FC-C679-4FF2-A62B-3FA63CCF185B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "55AB34FC-C679-4FF2-A62B-3FA63CCF185B", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
,AppContextTests finished
All tests finished
All tests finished
,2017-08-02 13:34:19 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.566400051116943
2017-08-02 13:34:19 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-08-02 13:34:19 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:55AB34FC-C679-4FF2-A62B-3FA63CCF185B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "55AB34FC-C679-4FF2-A62B-3FA63CCF185B", generation: 0)
,2017-08-02 13:34:22 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-02 13:34:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-02 13:34:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-02 13:34:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-02 13:34:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-02 13:34:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-02 13:34:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-02 13:34:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-02 13:34:26 - DEBUG CoordinatedClient: 'connected to the test server'
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
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-02 13:34:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
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
2017-08-02 13:34:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
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
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
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
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B25FF15-BE10-49F2-B4F6-3AD01FB9E662
[ThaliCore] Browser.startListening
2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 63 Can call stopListeningForAdvertisements without error
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A619F2DB-5920-4463-971B-49A802816CFF
[ThaliCore] Browser.startListening
,2017-08-02 13:34:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:34:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:34:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:34:59 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-02 13:34:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C0C5EE85-3DC1-4321-A926-76E28509F309", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C0C5EE85-3DC1-4321-A926-76E28509F309
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:03, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:C0C5EE85-3DC1-4321-A926-76E28509F309
2017-08-02 13:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:03 - INFO thaliMobil,e,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71074F78-E767-4392-92E9-88679F897AB6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:71074F78-E767-4392-92E9-88679F897AB6
2017-08-02 1,3:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71074F78-E767-4392-92E9-88679F897AB6", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:71074F78-E767-4392-92E9-88679F897AB6
2017-08-02 13:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:71074F78-E767-4392-92E9-88679F897AB6
,[ThaliCore] Advertiser.stopAdvertising() peerID:71074F78-E767-4392-92E9-88679F897AB6
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:35:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:35:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:35:09 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ED60016B-7091-44FC-9A9B-74EEA528D285", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ED60016B-7091-44FC-9A9B-74EEA528D285
2017-08-02 13:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:12, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-08-02 13:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:03ACB067-A6F9-47B0-8F41-CC86A2FCEE4F
[ThaliCore] Browser.startListening
2017-08-02 13:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advert,isingActive":true}'
2017-08-02 13:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EECE896-6DA2-4ED3-9377-AA8EDCC67D79:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EECE896-6DA2-4ED3-9377-AA8EDCC67D79", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15D5145B-E249-4A5F-B306-CF7DADB80079:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15D5145B-E249-4A5F-B306-CF7DADB80079", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED60016B-7091-44FC-9A9B-74EEA528D285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED60016B-7091-44FC-9A9B-74EEA528D285", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:35:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ED60016B-7091-44FC-9A9B-74EEA528D285
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7C550145-A750-4414-8AE2-913CC31E1F62
2017-08-02 1,3:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B5E2CB85-18AA-4585-90E3-3FE0CFDA5F86
[Thal,i,Core] Browser.startListening
,2017-08-02 13:35:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:35:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:35:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C550145-A750-4414-8AE2-913CC31E1F62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"544E1963-72AB-4976-83C3-D98BB4166601","generation":0}'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 544E1963-72AB-4976-83C3-D98BB4166601 (syncValue: pHrqA4ezETNZEmt24A0Jk8NeQM3pOt00)'
,2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18EAED4C-36F9-42F4-85C3-9F97B529CE7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18EAED4C-36F9-42F4-85C3-9F97B529CE7D", generation: 0)
2017-08-02 13:35:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18EAED4C-36F9-42F4-85C3-9F97B529CE7D","generation":0}'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6
[Thali,Core] Advertiser: session connected Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0,2CD7B60-D529-4BD1-84C7-064615D6C7E6 state: notConnected -> connecting
2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6
,[ThaliCore] Session.session(_:peer:didChange:) peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49481
,2017-08-02 13:35:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pHrqA4ezETNZEmt24A0Jk8NeQM3pOt00","error":null,"portNumber":49481}'
,2017-08-02 13:35:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pHrqA4ezETNZEmt24A0Jk8NeQM3pOt00', error: 'null', listeningPort: '49481''
,2017-08-02 13:35:23 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-08-02 13:35:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 ,13:35:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7C550145-A750-4414-8AE2-9,13CC31E1F62
2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:544E1963-72AB-4976-83C3-D98BB4166601
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49481
,[ThaliCore] Session.disconnect() peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "7C550145-A750-4414-8AE2-913CC31E1F62", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:02CD7B60-D529-4BD1-84C7-064615D6C7E6
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F810FD1D-5AEA-463E-8C18-4DA0A132C00B
2017-08-02 1,3:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5FA90361-C9DD-4207-94B1-CBFF76BDB73D
[Thal,i,Core] Browser.startListening
2017-08-02 13:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:26 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"544E1963-72AB-4976-83C3-D98BB4166601","generation":0}'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 544E1963-72AB-4976-83C3-D98BB4166601 (syncValue: R2GEqSBjaioQ9FvpXHfjzkcm2etPTTRM)'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F810FD1D-5AEA-463E-8C18-4DA0A132C00B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E06C374-CB3C-4D19-9DBC-249F54A9464A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:03768CE9-40C2-463B,-93B4-8F5364C40B1B:0
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
2017-08-02 13:35:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"03768CE9-40C2-463B-93B4-8F5364C40B1B","generation":0}'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
[ThaliCore] Advertiser: session connected Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,4E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,44E1963-72AB-4976-83C3-D98BB4166601", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
[ThaliCore] Session.startOutputStream(with:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-02 13:35:31 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:544E1963-72AB-4976-83C3-D98BB4166601:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,4E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,44E1963-72AB-4976-83C3-D98BB4166601", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "544E1963-72AB-4976-83C3-D98BB4166601", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:35:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R2GEqSBjaioQ9FvpXHfjzkcm2etPTTRM","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:35:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R2GEqSBjaioQ9FvpXHfjzkcm2etPTTRM', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:35:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:35:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1E06C374-CB3C-4D19-9DBC-249F54A9464A (syncValue: 9xlGJpYXFRdFTki8gqQwauT,Zy23BhvHX)'
2017-08-02 13:35:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E06C374-CB3C-4D19-9DBC-249F5,4A9464A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:544E1963-72AB-4976-83C3-D98BB4166601:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49492
,2017-08-02 13:35:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9xlGJpYXFRdFTki8gqQwauTZy23BhvHX","error":null,"portNumber":49492}'
,2017-08-02 13:35:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9xlGJpYXFRdFTki8gqQwauTZy23BhvHX', error: 'null', listeningPort: '49492''
,Connecting to the localhost:49492
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,Connected to the localhost:49492
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-02 13:35:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,ok 88 got the same data back
,# teardown
,2017-08-02 13:35:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:F810FD1D-5AEA-463E-8C18-4DA0A132C00B
2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13,:,35:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49492
[ThaliCore] Session.disconnect() p,eer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F810FD1D-5AEA-463E-8C18-4DA0A132C00B", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:CD65D8B7-AA01-4284-BFC0-DFD14F318866
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AD28B5DB-E788-401E-9F57-0536CE0FD977
2017-08-02 1,3:35:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F93769B-EFD4-42BB-BF80-0611E470C666
[Thal,i,Core] Browser.startListening
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:35:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:35:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"03768CE9-40C2-463B-93B4-8F5364C40B1B","generation":0}'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 03768CE9-40C2-463B-93B4-8F5364C40B1B (syncValue: VznH3ZFxsElLFc957QN8HQ04qtiWo6Cc)'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1E06C374-CB3C-4D19-9DBC-249F54A9464A","generation":0}'
2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AD28B5DB-E788-401E-9F57-0536CE0FD977:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3437029A-5592-425D-88F9-94BA127A2E7C","generation":0}'
,2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3", generation: 0)
2017-08-02 13:35:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3AAC3A35-ACDB-4760-AEA7-5C08AC335BC3","generation":0}'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03,768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,3768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1E06C374-CB3C-4D19-9DBC-249F54A9464A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1E06C374-CB3C-4D19-9DBC-249F54A9464A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03,768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,3768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03,768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,3768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03,768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "03768CE9-40C2-463B-93B4-8F5364C40B1B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:03768CE9,-40C2-463B-93B4-8F5364C40B1B error: max retries exceeded
2017-08-02 13:35:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VznH3ZFxsElLFc957QN8HQ04qtiWo6Cc","error":"Connection could not be established","portNumber":null}'
2017-0,8-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VznH3ZFxsElLFc957QN8HQ04qtiWo6Cc', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-02 13:35:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3437029A-5592-425D-88F9-94BA127A2E7C (syncValue: Z3JwPPQ,jFHOTn6L5sHbaaa3o6bKxewgH)'
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3437029A-5592,-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:35:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:03768CE9-40C2-463B-93B4-8F5364C40B1B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] Advertiser: session connected Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49508
2017-08-02 13:35:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z3JwPPQjFHOTn6L5sHbaaa3o6bKxewgH",,"error":null,"portNumber":49508}'
2017-08-02 13:35:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z3JwPPQjFHOTn6L5sHbaaa3o6bKxewgH', error: 'null', listeningPort: '49508''
Connecting to the localhost:49508
Connecting to th,e localhost:49508
Connecting to the localhost:49508
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
Connected to the localhost:49508
[ThaliCore] Session.startOutputStream(with:) peer:3437029A-5592-,425D-88F9-94BA127A2E7C:0
[ThaliCore] Session.startOutputStream(with:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
Connected to the localhost:49508
,Connected to the localhost:49508
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1 state: connecting -> connected
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
ok 96 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] Session.startOutputStream(with:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] Session.startOutputStream(with:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] Session.startOutputStream(with:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 4, 5, 7, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 4, 5, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-02 13:35:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 4, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-02 13:35:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5]
[ThaliCore], AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:AD28B5DB-E788-401E-9F57-0536CE0FD977
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3437029A-5592-425D-88F9-94BA127A2E7C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49508
[ThaliCore] Session.disconnect() p,eer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "AD28B5DB-E788-401E-9F57-0536CE0FD977", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] Session.deinit peer:D3CF5DF6-B4B3-4EE1-95B4-68DA423FEEF1
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6133E365-15A1-4D8C-9D13-580E318DED29
,2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1BF6993A-3DF0-47D2-9B9E-BAB46F9A4614
[ThaliCore] Browser.startListening
2017-08-02 13:35:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:35:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:35:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
2017-08-02 13:35:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3437029A-5592-425D-88F9-94BA127A2E7C","generation":0}'
2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3437029A-5592-425D-88F9-94BA127A2E7C (syncValue: vP7UZTix1j3Mh7240zFNWA2OHL288u8C)'
,2017-08-02 13:35:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "34,37029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
2017-08-02 13:36:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
2017-08-02 13:36:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6133E365-15A1-4D8C-9D13-580E318DED29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35268274-9198-49CF-822E-A7FA7B1EE03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35268274-9198-49CF-822E-A7FA7B1EE03C", generation: 0)
2017-08-02 13:36:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35268274-9198-49CF-822E-A7FA7B1EE03C","generation":0}'
2017-08-02 13:36:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-02 13:36:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3437029A-5592-425D-88F9-94BA127A2E7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:34,37029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,437029A-5592-425D-88F9-94BA127A2E7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3437029A-5592-425D-88F9-94BA127A2E7C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:36:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vP7UZTix1j3Mh7240zFNWA2OHL288u8C","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:36:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vP7UZTix1j3Mh7240zFNWA2OHL288u8C', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:36:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:36:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A2FAD16-B69B-48BB-8217-693632C78C14 (syncValue: cZyKWdvpizSCQj42vmUBdor,A27PVoLDT)'
2017-08-02 13:36:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-69363,2C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3437029A-5592-425D-88F9-94BA127A2E7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075
[ThaliCore] Advertiser: session connected Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
[ThaliCore] Advertiser: session connected Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49527
,2017-08-02 13:36:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cZyKWdvpizSCQj42vmUBdorA27PVoLDT","error":null,"portNumber":49527}'
,2017-08-02 13:36:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cZyKWdvpizSCQj42vmUBdorA27PVoLDT', error: 'null', listeningPort: '49527''
,Connecting to the localhost:49527
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 5, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49527
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-02 13:36:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075
,[ThaliCore] Session.startOutputStream(with:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 5, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
,[ThaliCore] Session.session(_:peer:didChange:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
[ThaliCore] Session.startOutputStream(with:) peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 5, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-02 13:36:13 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited R,unLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 5, 9, 10]
,2017-08-02 13:36:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6133E365-15A1-4D8C-9D13-580E318DED29
2017-08-0,2 13:36:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2A2FAD16-B69B-48BB-8217-693632C78C14
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49527
[ThaliCore] Session.disconnect() p,eer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEA6E48-F596-4C5D-9716-66E488CE4075 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6133E365-15A1-4D8C-9D13-580E318DED29", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:A2D3518E-F240-441A-B0ED-FA6300D2149E
,[ThaliCore] AdvertiserRelay.deinit
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3354EF96-D625-4161-8D00-E338DDA254DF
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C48CFE58-829C-494C-B1A6-009DC5C2F39F
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:36:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:36:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
2017-08-02 13:36:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2A2FAD16-B69B-48BB-8217-693632C78C14","generation":0}'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2A2FAD16-B69B-48BB-8217-693632C78C14 (syncValue: oQjTNO8BUmAf9CxYBBUuyaKtMafz0Fyo)'
2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3354EF96-D625-4161-8D00-E338DDA254DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6416A01-7433-4745-962F-A44CFEAB83C5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6416A01-7433-4745-962F-A44CFEAB83C5", generation: 0)
,2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A6416A01-7433-4745-962F-A44CFEAB83C5","generation":0}'
,2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:36:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275
[ThaliCore] Advertiser: session connected Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275
[ThaliCore] Session.startOutputStream(with:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 5, 9, 10, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (4238 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (25600 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received (729 bytes):'
,2017-08-02 13:36:21 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:36:22 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-02 13:36:22 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 5, 9, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A2FAD16-B69B-48BB-8217-693632C78C14", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:36:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oQjTNO8BUmAf9CxYBBUuyaKtMafz0Fyo","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:36:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oQjTNO8BUmAf9CxYBBUuyaKtMafz0Fyo', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:36:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:36:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 57015E63-23BD-4EB8-8492-2EBC0DAADB25 (syncValue: DJ9kvDEQLrNs0dPoEa7Wxak,HvQY5l43a)'
2017-08-02 13:36:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:57015E63-23BD-4EB8-8492-2EBC0,DAADB25:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:36:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2A2FAD16-B69B-48BB-8217-693632C78C14:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
[ThaliCore] Advertiser: session connected Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49544
,2017-08-02 13:36:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DJ9kvDEQLrNs0dPoEa7WxakHvQY5l43a","error":null,"portNumber":49544}'
,2017-08-02 13:36:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DJ9kvDEQLrNs0dPoEa7WxakHvQY5l43a', error: 'null', listeningPort: '49544''
,Connecting to the localhost:49544
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,Connected to the localhost:49544
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 5, 9, 10, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-02 13:36:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
,[ThaliCore] Session.session(_:peer:didChange:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
[ThaliCore] Session.startOutputStream(with:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 5, 9, 10, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (33945 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (3569 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (6144 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (2758 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received (4287 bytes):'
,2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-02 13:36:28 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 5, 9, 10, 13]
,2017-08-02 13:36:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3354EF96-D625-4161-8D00-E338DDA254DF
,[ThaliCore] Session.session(_:peer:didChange:) peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
[ThaliCore] Advert,iserRelay.deinit
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49544
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A1DAA20B-BD4A-4554-8761-EBC0F6CF9275 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3354EF96-D625-4161-8D00-E338DDA254DF", generation: 0)
,# setup
,2017-08-02 13:36:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DJ9kvDEQLrNs0dPoEa7WxakHvQY5l43a","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:15328036-B9D1-4DEB-ADFA-F3CBEFC39B6B
,[ThaliCore] Session.deinit peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F598F822-3203-44DC-8801-E65D72E927ED
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:36:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A6416A01-7433-4745-962F-A44CFEAB83C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A6416A01-7433-4745-962F-A44CFEAB83C5", generation: 0)
2017-08-02 13:36:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A6416A01-7433-4745-962F-A44CFEAB83C5","generation":0}]'
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A6416A01-7433-4745-962F-A44CFEAB83C5","generation":0}'
2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}]'
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}'
,2017-08-02 13:36:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:57015E63-23BD-4EB8-8492-2EBC0DAADB25:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "57015E63-23BD-4EB8-8492-2EBC0DAADB25", generation: 0)
2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}]'
2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"57015E63-23BD-4EB8-8492-2EBC0DAADB25","generation":0}'
2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Br,owser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AAC7114D-9198-4417-ABCB-FAF457EC1EA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AAC7114D-9198-4417-ABCB-FAF457EC1EA7", generation: 0)
2017-08-02 13:36:32 - DEBUG thaliMobileNat,iveWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AAC7114D-9198-4417-ABCB-FAF457EC1EA7","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF1643D-E6BB-4CD,0-AF7F-003E6A7880B8:0
2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AAC7114D-9198-4417-ABCB-FAF457EC1EA7","generation":0}'
[ThaliCore] BrowserManager.foundPeer,Handler peer:Peer(uuid: "2DF1643D-E6BB-4CD0-AF7F-003E6A7880B8", generation: 0)
,2017-08-02 13:36:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41D3B57A-35E7-466F-9DBF-DA142AC44F5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41D3B57A-35E7-466F-9DBF-DA142AC44F5C", generation: 0)
2017-08-02 13:36:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"41D3B57A-35E7-466F-9DBF-DA142AC44F5C","generation":0}]'
2017-08-02 13:36:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"41D3B57A-35E7-466F-9DBF-DA142AC44F5C","generation":0}'
2017-08-02 13:36:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 ,13:36:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2DF1643D-E6BB-4CD0-AF7F-0,03E6A7880B8
2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3FD0F702-BB61-4D27-BC29-1DEA8C8D8BB8
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C0134B5-2AC3-49BF-9277-F01262384061", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C0134B5-2AC3-49BF-9277-F01262384061
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0C0134B5-2AC3-49BF-9277-F01262384061
ok ,111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:36:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-02 13:36:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-02 13:36:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-02 13:36:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9c2a6b80-8289-496f-944e-815d65b6cc05 error: startListeningNotActive
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"l9hdQ9UwihT7YKW8VMpFJm52wlPIWJnX","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:36:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:36:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F634D46-F3C9-4A43-8491-2A0B606947DC
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2ZKUuqunkuVRHfYce15q7VF5c41lQ3oe","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C4E11F18-2A9A-4D81-B8D4-C0B097209440
,[ThaliCore] Browser.startListening
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:36:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02, 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:36:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:36:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:3d63a5b1-1f45-42f4-8c57-edd2395d6a9d
,ok 140 No error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:69DFFFC2-5186-4945-983D-DB6839F2BF34
2017-08-02 1,3:36:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:36:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4C0E8F9D-7F20-4990-B0D6-35B5449DA4C3
[ThaliCore] Browser.startListening
2017-08-02 13:36:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:36:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:36:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DFFFC2-5186-4945-983D-DB6839F2BF34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2D5EA3C1-2612-4C80-833C-86BA8D46ADA6","generation":0}'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2D5EA3C1-2612-4C80-833C-86BA8D46ADA6 (syncValue: whyrOVVn5uey3avkKlm9bWBw7fXejfzR)'
,2017-08-02 13:36:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B1240C8D-B477-419D-98C6-0B92452098A6","generation":0}'
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:36:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49552
2017-08-02 13:36:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"whyrOVVn5uey3avkKlm9bWBw7fXejfzR",,"error":null,"portNumber":49552}'
2017-08-02 13:36:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'whyrOVVn5uey3avkKlm9bWBw7fXejfzR', error: 'null', listeningPort: '49552''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) found active relay
,2017-08-02 13:36:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CoFDtPyChZTpDi31ozko1ouzkyTeK20s","error":null,"portNumber":49552}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0) found active relay
,2017-08-02 13:36:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fGCcgilEXf4C16uXIMhOyNoOaIFLpy9N","error":null,"portNumber":49552}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 5, 9, 10, 13, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
[ThaliCore] Advertiser: session connected Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
,[ThaliCore] Session.session(_:peer:didChange:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
[ThaliCore] Session.startOutputStream(with:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 5, 9, 10, 13, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:36:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:36:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16,
[ThaliCore] VirtualSocket.closeStreams() vsID:16
2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() pee,rID:69DFFFC2-5186-4945-983D-DB6839F2BF34
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] VirtualSocket exited RunLoop vsID:,16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 3, 5, 9, 10, 13, 15]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 5, 9, 10, 13]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.disconnect peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49552
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "2D5EA3C1-2612-4C80-833C-86BA8D46ADA6", generation: 0)
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateU,pdateNonTCP registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-02 13:36:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"whyrOVVn5uey3avkKlm9bWBw7fXejfzR","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "69DFFFC2-5186-4945-983D-DB6839F2BF34", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2D5EA3C1-2612-4C80-833C-86BA8D46ADA6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:19DE0C72-4053-401B-9A8A-EE6CE66C33B1
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
,2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:36:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:36:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:36:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 49556'
,ok 149 Should throw
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'listening 49558'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-02 13:36:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-02 13:36:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 49561'
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
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'listening 49565'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 49570'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:36:58 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-08-02 13:36:58 - DEBUG createNativeListener: 'listening 49574'
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
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 49578'
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
2017-08-02 13:36:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 49582'
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
,2017-08-02 13:36:59 - DEBUG createNativeListener: 'listening 49586'
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
2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node ,- 0 - 2 - close'
2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-08-02 13:37:00 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client c,onnection to node - 0 - 0 - close'
,# teardown
,2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:01 - DEBUG createNativeListener: 'listening 49638'
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
2017-08-02 13:37:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:01 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:02 - DEBUG createNativeListener: 'listening 49642'
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
,ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 49645'
,ok 196 port must be in range
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 49646'
,ok 197 second start should return same port
,# teardown
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-02 13:37:03 - DEBUG createNativeListener: 'listening 49648'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-08-02 13:37:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-08-02 13:37:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-02 13:37:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-08-02 13:37:04 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 49650
,ok 207 should be equal
# teardown
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4A952A36-869C-4BA1-B6B2-B18200FBF636
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC95A3D5-4F19-4144-80B3-3BCBE1B0E02E
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
2017-08-02 13:37:04 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}}),'
,2017-08-02 13:37:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B1240C8D-B477-419D-98C6-0B92452098A6","generation":0}'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B1240C8D-B477-419D-98C6-0B92452098A6 (syncValue: 9YF7rXJ5WK0COAzymp9FK1ot7GZBFvzL)'
,2017-08-02 13:37:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E","generation":0}'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C712BB72-1ECB-455C-8BB1-65EBA45DEC6A","generation":0}'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A952A36-869C-4BA1-B6B2-B18200FBF636:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,1240C8D-B477-419D-98C6-0B92452098A6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,1240C8D-B477-419D-98C6-0B92452098A6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1240C8D-B477-419D-98C6-0B92452098A6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,1240C8D-B477-419D-98C6-0B92452098A6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B1240C8D-B477-419D-98C6-0B92452098A6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9YF7rXJ5WK0COAzymp9FK1ot7GZBFvzL","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9YF7rXJ5WK0COAzymp9FK1ot7GZBFvzL', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E (syncValue: 5J8IEjRz1IAJZnhhAwqAIlo,48GQM6bGT)'
2017-08-02 13:37:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E,900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-02 13:37:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B1240C8D-B477-419D-98C6-0B92452098A6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4
[ThaliCore] Advertiser: session connected Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49662
2017-08-02 13:37:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5J8IEjRz1IAJZnhhAwqAIlo48GQM6bGT",,"error":null,"portNumber":49662}'
2017-08-02 13:37:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5J8IEjRz1IAJZnhhAwqAIlo48GQM6bGT', error: 'null', listeningPort: '49662''
,ok 210 should be equal
,2017-08-02 13:37:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C712BB72-1ECB-455C-8BB1-65EBA45DEC6A (syncValue: X180ZgVoiFsdA9BSiuA1wPkfiDsywodk)'
,2017-08-02 13:37:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9326440E-49A8-4DC5-9049-885DBB40813A
[ThaliCore] Advertiser: session connected Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] Session.session(_:peer:,didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49666
,2017-08-02 13:37:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X180ZgVoiFsdA9BSiuA1wPkfiDsywodk","error":null,"portNumber":49666}'
,2017-08-02 13:37:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X180ZgVoiFsdA9BSiuA1wPkfiDsywodk', error: 'null', listeningPort: '49666''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9326440E-49A8-4DC5-9049-885DBB40813A
,[ThaliCore] Session.session(_:peer:didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4A952A36-869C-4BA1-B6B2-B18200FBF636
2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49662
,[ThaliCore] Session.disconnect() peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:49666
[ThaliCore] Session.disconnect() peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A
,2017-08-02 13:37:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
[ThaliCore] Session.session(_:peer:didChange:) peer:9326440E-49A8-4DC5-9049-885DBB40813A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
[ThaliCore] ,AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9326440E-49A8-4DC5-9049-885DBB40813A
[ThaliCor,e] AdvertiserRelay.deinit
2017-08-02 13:37:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X180ZgVoiFsdA9BSiuA1wPkfiDsywodk","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:9326440E-49A8-4DC5-9049-885DBB40813A
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07E8E38-F7B6-45B9-A070-2A2492D7E5B4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A952A36-869C-4BA1-B6B2-B18200FBF636", generation: 0)
,# Multiple local http requests
,listening on 49668
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
2017-08-0,2 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:00DC2AB4-228C-4A26-A795-434E1581F9F6
2017-08-02 1,3:37:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:114D954D-133E-477A-A2FB-8DF94A6BD274
[ThaliCore] Browser.startListening
2017-08-02 13:37:25 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C712BB72-1ECB-455C-8BB1-65EBA45DEC6A","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C712BB72-1ECB-455C-8BB1-65EBA45DEC6A (syncValue: oYk99ROw5BG0WDgySWPLUeZzds3vxCcA)'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E","generation":0}'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
,2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0A7596E-3DFD-4990-A0F0-BB946745D9EF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38E,B4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00DC2AB4-228C-4A26-A795-434E1581F9F6:0
2017-08-02 1,3:37:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", g,eneration: 0)
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C7,12BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C712BB72-1ECB-455C-8BB1-65EBA45DEC6A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oYk99ROw5BG0WDgySWPLUeZzds3vxCcA","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oYk99ROw5BG0WDgySWPLUeZzds3vxCcA', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E (syncValue: 6vdECDfpsEjExePRKgyC1Ty,PJ5TJGevi)'
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E,900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-02 13:37:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C712BB72-1ECB-455C-8BB1-65EBA45DEC6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,E5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,CE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,E5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,CE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CC,E5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,CE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:37:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6vdECDfpsEjExePRKgyC1TyPJ5TJGevi","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6vdECDfpsEjExePRKgyC1TyPJ5TJGevi', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:37:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0A7596E-3DFD-4990-A0F0-BB946745D9EF (syncValue: ncVdNuDP3hVGzm0gA1d3Oic,qYhhXLTZO)'
2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0A7596E-3DFD-4990-A0F0-BB946,745D9EF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:37:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CCE5AE9E-6A2F-4382-99A8-BB35E900BC6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0A7596E-3DFD-4990-A0F0-BB946745D9EF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49685
2017-08-02 13:37:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ncVdNuDP3hVGzm0gA1d3OicqYhhXLTZO",,"error":null,"portNumber":49685}'
2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ncVdNuDP3hVGzm0gA1d3OicqYhhXLTZO', error: 'null', listeningPort: '49685''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 38EB4510-C4BB-4339-8267-E8BFF2A630EC (syncValue: dZNk9UXmvXD3T4TFateUqfUHbPEoMti3)'
,2017-08-02 13:37:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
[ThaliCore] Advertiser: session connected Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49690
,2017-08-02 13:37:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dZNk9UXmvXD3T4TFateUqfUHbPEoMti3","error":null,"portNumber":49690}'
2017-08-02 13:37:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd,ZNk9UXmvXD3T4TFateUqfUHbPEoMti3', error: 'null', listeningPort: '49690''
,ok 220 should be equal
ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Advertiser: session connected Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00DC2AB4-228C-4A26-A795-434E1581F9F6
2017-08-02 13:37:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF,
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49685
,[ThaliCore] Session.disconnect() peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:94B9F7F2-9417-48C7-A5B2-E572F8D3A1CE
[ThaliCore] Session.deinit peer:D0A7596E-3DFD-4990-A0F0-BB946745D9EF:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49690
[ThaliCore] Session.disconnect() peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserRelay.deinit
2017-08-02 13:37:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered ,to native'
,2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4818CFC3-52BB-48B5-8FD1-E7E06BE326B0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "00DC2AB4-228C-4A26-A795-434E1581F9F6", generation: 0)
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'listening 49694'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07736D71-3F61-4091-81CE-87DAF7E94316
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:37:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 49695'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3C9D6DAE-5ECA-4571-A98F-A5C1652FC745", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3C9D6DAE-5ECA-4571-A98F-A5C1652FC745
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 231 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3C9D6DAE-5ECA-4571-A98F-A5C1652FC745", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:3C9D6DAE-5ECA-4571-A98F-A5C1652F,C745
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:37:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3C9D6DAE-5ECA-4571-A98F-A5C1652FC745
,[ThaliCore] Advertiser.stopAdvertising() peerID:3C9D6DAE-5ECA-4571-A98F-A5C1652FC745
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 233 must be stopped
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
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'listening 49698'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'listening 49699'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF08245F-33A5-4603-914D-4B74EABBC96F
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:37:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F2C970FB-3BA,5-4C04-A0F8-5B30DCF5791B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F2C970FB-3BA5-4C04-A0F8-5B30DCF5791B
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F2C970FB-3BA5-4C04-A0F8-5B30DCF5791B
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'listening 49702'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69C82386-4ABD-45ED-A32E-6042A1658C38
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22F99005-C971-40D9-B466-78FA1AD235C2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:22F99005-C971-40D9-B466-78FA1AD235C2
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:37:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:22F99005-C971-40D9-B466-78FA1AD235C2
,2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-08-02 13:37:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:37:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'listening 49704'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EBA4F060-D0C4-41D9-80A2-14672573F46A
,[ThaliCore] Browser.startListening
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "96291A9D-6251-4629-A9A9-9A38BC0C32D4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:96291A9D-6251-4629-A9A9-9A38BC0C32D4
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:96291A9D-6251-4629-A9A9-9A38BC0C32D4
,2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:37:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:37:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:37:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
2017-08-02 13:37:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:37:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:37:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:37:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:37:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:37:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:38:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 49707'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:228B517B-BCA1-44A7-97EC-70FFB52932B5
[ThaliCore] Browser.st,artListening
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive matches
ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 49708'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C29E436A-1683-4B2D-B450-935634583CC7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C29E436A-1683-4B2D-B450-935634583CC7
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C29E436A-1683-4B2D-B450-935634583CC7
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'listening 49710'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'listening 49711'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:553F4E7B-61E6-493F-9BF2-47D75281DFA4
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFE11449-403B-465C-8474-A0A7BD88124B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CFE11449-403B-465C-8474-A0A7BD88124B
2017-08-02 13:38:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:38:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-02 13:38:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
2017-08-02 13:38:03 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5054820D-90EB-4D0B-9C85-F5A7951960E1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5054820D-90EB-4D0B-9C85-F5A7951960E1", generation: 0)
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","generation":0}]'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFE11449-403B-465C-8474-A0A7BD88124B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFE11449-403B-465C-8474-A0A7BD88124B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
2017-08-02 13:38:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}]'
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
,2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CFE11449-403B-465C-8474-A0A7BD88124B
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:03 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:03 - DEBUG thaliMob,ileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:03 - DEBUG mak,eIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-02 13:38:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'listening 49713'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2A3826C-A35E-4C46-B429-74AFA0F4C0FD
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-02 13:38:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-02 13:38:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44,F1-BCC5-45677AFEBDAC","generation":0}]'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4214F04-2954-44F1-BCC5-45677AFEBDAC (syncValue: ZS7jspKszGmzsdeO3x4nfFFdSUexisfo)'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}]'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
[ThaliCore] Advertiser: session connected Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F9B6F57-AB39-4527-81DB-C997CCB7CD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F9B6F57-AB39-4527-81DB-C997CCB7CD5C", generation: 0)
2017-08-02 13:38:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}]'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","generation":0}'
,2017-08-02 13:38:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
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
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
,2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}]'
,2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","generation":0}'
,2017-08-02 13:38:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-02 13:38:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4214F04-2954-44F1-BCC5-45677AFEBDAC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
[ThaliCore] Session.startOutputStream(with:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 5, 9, 10, 13, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B4,214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4214F04-2954-44F1-BCC5-45677AFEBDAC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-08-02 13:38:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZS7jspKszGmzsdeO3x4nfFFdSUexisfo","error":"Peer is unavailable","portNumber":null}'
2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZS7jspKszGmzsdeO3x4nfFFdSUexisfo', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:38:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 38EB4510-C4BB-4339-8267-E8BFF2A630EC (syncValue: iAKbTaui4mcNRWz36hyl3wg2c0YFOBW8)'
2017-08-02 13:38:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B4214F04-2954-44F1-BCC5-45677AFEBDAC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
2017-08-02 13:38:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}]'
2017-08-02 13:38:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","generation":0}'
,2017-08-02 13:38:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-02 13:38:13 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"38EB4510-C4BB-4339-8267-E8BFF2A630EC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,8EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "38EB4510-C4BB-4339-8267-E8BFF2A630EC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-02 13:38:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iAKbTaui4mcNRWz36hyl3wg2c0YFOBW8","error":"Peer is unavailable",,"portNumber":null}'
2017-08-02 13:38:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iAKbTaui4mcNRWz36hyl3wg2c0YFOBW8', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-02 13:38:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-02 13:38:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679 (syncValue: k1M1tTMSzPfRYAjaXDKERUK,5cypbl74F)'
2017-08-02 13:38:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833,B9D6679:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:38EB4510-C4BB-4339-8267-E8BFF2A630EC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49722
2017-08-02 13:38:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k1M1tTMSzPfRYAjaXDKERUK5cypbl74F",,"error":null,"portNumber":49722}'
2017-08-02 13:38:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'k1M1tTMSzPfRYAjaXDKERUK5cypbl74F', error: 'null', listeningPort: '49722''
,2017-08-02 13:38:16 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 5, 9, 10, 13, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:17 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:17 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02, 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49722
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Session.disconnect() peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 5, 9, 10, 13, 17]
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Session.deinit peer:B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679:0
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Virt,ualSocket.deinit vsID:17 [1, 3, 5, 9, 10, 13]
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-02 13:38:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-02 13:38:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-02 13:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "75362F1E-B9D2-4EFB-AF5E-0D4E56228E2E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:8FBFA9F4-57BE-4E10-B4BA-3AE4CF01E950
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-02 13:38:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-02 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5054820D-90EB-4D0B-9C85-F5A7951960E1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B8B1B7E3-CFBF-4090-9ADB-F4833B9D6679","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:38:20 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5F9B6F57-AB39-4527-81DB-C997CCB7CD5C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 49724'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 297 error should be null
,ok 298 error should be null
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
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'listening 49725'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D2473C0-4330-4758-9177-17ECD1A3F764
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-02 13:38:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 49726'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC1EF316-6568-4346-A5BC-A06F1CD67743", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DC1EF316-6568-4346-A5BC-A06F1CD67743
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
,ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC1EF316-6568-4346-A5BC-A06F1CD67743", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DC1EF316-6568-4346-A5BC-A06F1CD67743
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DC1EF316-6568-4346-A5BC-A06F1CD67743
[ThaliCore] Advertiser.stopAdvertising() peerID:DC1EF316-6568-4346-A5BC-A06F1CD67743
2017-08-02 13:38:21 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-08-02 13:38:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-02 13:38:21 - DEBUG thaliMobileNativeWrapper: 'listening 49729'
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
,2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-02 13:38:22 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'listening 49730'
,ok 330 first call should succeed
,ok 331 first call should succeed
,ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-02 13:38:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-02 13:38:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c3bb5113-45f3-4aa1-8389-3d445619262d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 342 should be calle,d once
ok 343 should not have been called more than once
,# teardown
,2017-08-02 13:38:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c3bb5113-45f3-4aa1-8389-3d445619262d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7725b9b5-c056-4c40-a218-f9a599c34cef","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 352 peer should be available
ok 353 cache contains native peer
2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7725b9b5-c056-4c40-a218-f9a599c34cef","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
,2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21973f4b-eb38-4d58-9614-6929ba7fbd69","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 360 peer should be available
,ok 361 cache contains wifi peer
,2017-08-02 13:38:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21973f4b-eb38-4d58-9614-6929ba7fbd69","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d96cce1c-4fff-47ff-b472-ddd8c92880cb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d95521e-1ee4-4816-bc4d-28b7994d6950","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d96cce1c-4fff-47ff-b472-ddd8c92880cb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3d95521e-1ee4-4816-bc4d-28b7994d6950","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9e69974f-7d6b-41a5-8d2a-90ad77c5c5a9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-08-02 13:38:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9e69974f-7d6b-41a5-8d2a-90ad77c5c5a9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-08-02 13:38:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-08-02 13:38:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c53d3821-5833-4c44-9986-abf9226b0535","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 384 peer should be available
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c53d3821-5833-4c44-9986-abf9226b0535","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be available
ok 386 should store correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c53d3821-5833-4c44-9986-abf9226b0535","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'listening 49731'
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a60af51-fef1-4360-8559-6a7bbaa44149","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 discovered correct peer
,ok 391 got correct generation
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a60af51-fef1-4360-8559-6a7bbaa44149","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-08-02 13:38:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1a60af51-fef1-4360-8559-6a7bbaa44149","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-08-02 13:38:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'listening 49732'
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f6ac812-7193-40c2-a175-764eccbf7bc8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f6ac812-7193-40c2-a175-764eccbf7bc8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-08-02 13:38:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2aa5724-2c6a-49bd-9f90-e9b7d6460da5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2aa5724-2c6a-49bd-9f90-e9b7d6460da5","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-08-02 13:38:27 - DEBUG thaliMobileNativeWrapper: 'listening 49733'
2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e18b50b0-5549-4bd3-a990-a714ac074f3c","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9d790e49-c209-4f29-bc39-d63ec032d7c8","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9d790e49-c209-4f29-bc39-d63ec032d7c8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9d790e49-c209-4f29-bc39-d63ec032d7c8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-08-02 13:38:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9d790e49-c209-4f29-bc39-d63ec032d7c8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e18b50b0-5549-4bd3-a990-a714ac074f3c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-02 13:38:28 - DEBUG thaliMobileNativeWrapper: 'listening 49734'
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2fe2d19d-ea32-4376-bb17-45d6817bc61f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b40b783e-bdb7-411e-8a3e-297ee05685d3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2fe2d19d-ea32-4376-bb17-45d6817bc61f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-08-02 13:38:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b40b783e-bdb7-411e-8a3e-297ee05685d3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-02 13:38:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33fd069e-5238-4720-b8ed-4b2f5b01a8fe","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33fd069e-5238-4720-b8ed-4b2f5b01a8fe","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33fd069e-5238-4720-b8ed-4b2f5b01a8fe","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 437 new port handled correctly
,2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33fd069e-5238-4720-b8ed-4b2f5b01a8fe","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled, correctly
2017-08-02 13:38:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"33fd069e-5238-4720-b8ed-4b2f5b01a8fe","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 new,AddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
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
ok 448 error should be null
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
,ok 455 error should be null
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
ok 460 contains expected properties
ok 461 the same hostAddress
ok 462 the same portNumber
,# teardown
,2017-08-02 13:38:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
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
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 49735'
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c92d5454-8b11-4e35-b373-5ef8de248032","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c92d5454-8b11-4e35-b373-5ef8de248032","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-02 13:38:32 - DEBUG thaliMobileNativeWrapper: 'listening 49736'
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"367bb4c8-d616-4f3a-b61e-fdaf380a54f8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:367bb4c8-d616-4f3a-b61e-fdaf380a54f8
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-08-02 13:38:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"367bb4c8-d616-4f3a-b61e-fdaf380a54f8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 482 error should be null
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
ok 494 error should be null
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
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'listening 49737'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA80F74E-C172-4A9D-B2BB-1AA70F18B58A
,[ThaliCore] Browser.startListening
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aa6f764c-96fd-4b9d-86c8-e456496d86af","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cb968e34-8bf1-49b8-acf4-66295b78f989","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"aa6f764c-96fd-4b9d-86c8-e456496d86af","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-02 13:38:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cb968e34-8bf1-49b8-acf4-66295b78f989","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:38:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-02 13:38:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'listening 49738'
2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5596c976-fd25-46bb-92c2-ca4abd0f3235","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"57ce7816-1937-471e-981a-53a7d32ba9ce","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-08-02 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5596c976-fd25-46bb-92c2-ca4abd0f3235","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"57ce7816-1937-471e-981a-53a7d32ba9ce","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-08-02 13:38:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
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
,2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'listening 49739'
,ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
[ThaliCore] Advertiser.startAdvertising with, peerID:8222BD6A-6049-42EA-8E3E-EADA99C64585
2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:22C031AA-D4EE-4D0C-A5BD-075CA882B9C4
[ThaliCore] Browser.startListening
2017-08-02 13:38:36 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
2017-08-02 13:38:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","generation":0}]'
2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","generation":0}'
,2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:38:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 8B2DDBB7-B3DF-467C-B63F-625FA51822DC (syncValue: 0)'
2017-08-02 13:38:37 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B2DDBB7-B3DF-467C,-B63F-625FA51822DC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8222BD6A-6049-42EA-8E3E-EADA99C64585:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","generation":0}]'
2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","generation":0}'
,2017-08-02 13:38:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:38:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8B2DDBB7-B3DF-467C-B63F-625FA51822DC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49742
,2017-08-02 13:38:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":49742}'
,2017-08-02 13:38:40 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1FFD57F3-189F-4C51-9BD0-1F96D486CC8B (syncValue: 1)'
,2017-08-02 13:38:40 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B2DDBB7-B3DF-467C-B63F-625FA51822DC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 5, 9, 10, 13, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:40 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:40 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1FFD57F3-189F-4C51-9BD0-1F96D486CC8B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49746
,2017-08-02 13:38:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":49746}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1FFD57F3-189F-4C51-9BD0-1F96D486CC8B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 5, 9, 10, 13, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-02 13:38:45 - DEBUG testUtils: 'Got response data'
,2017-08-02 13:38:45 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] Advertiser: session connected Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C421471F-9A7D-45A4-AB76-3A9780512700 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] Advertiser: session connected Peer(uuid: "8222BD6A-6049-42EA-8E3E-EADA99C64585", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C421471F-9A7D-45A4-AB76-3A9780512700 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] Session.startOutputStream(with:) peer:C421471F-9A7D-45A4-AB76-3A9780512700
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [1, 3, 5, 9, 10, 13, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
,[ThaliCore] Session.session(_:peer:didChange:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] Session.startOutputStream(with:) peer:54561342-FCEC-42D3-B0DF-2D9BEA207A87
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [1, 3, 5, 9, 10, 13, 19, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 5, 9, 10, 13, 20, 21, 22]
[ThaliCore] TCPListener.socketDidDisconnect(_:,withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[Th,aliCore] VirtualSocket.deinit vsID:20 [1, 3, 5, 9, 10, 13, 21, 22]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserR,elay.didSocketDisconnectHandler
,2017-08-02 13:38:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8B2DDBB7-B3DF-467C-B63F-625FA51822DC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:38:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1FFD57F3-189F-4C51-9BD0-1F96D486CC8B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8222BD6A-6049-42EA-8E3E-EADA99C64585
2017-08-02 13:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-08-02 13:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-02 13:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-02 13:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-02 13:38:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,ok 525 error should be null
,ok 526 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 5, 9, 10, 13, 22]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [1, 3, 5, 9, 10, 13]
,# setup
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-08-02 13:38:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
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
2017-08-02 13:38:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 545 agent's destroy should not be called again
ok 546 agent is destroyed
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
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
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
,ok 617 We are out of the pool
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
ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
,ok 628 1st action is out of the pool
,ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-08-02 13:39:11 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 631 Got right error
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
ok 637 Got null
,2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 638 is an agent
2017-08-02 13:39:12 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
ok 641 Got another null
2017-08-02 13:39:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 642 is an agent
2017-08-02 13:39,:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
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
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 647 should have gotten null
2017-08-02 13:39:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-08-02 13:39:14 - DEBUG thaliPeer,PoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 648 Should have stopped nicely
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
ok 674 generation should match
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
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
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
,ok 718 should be equal
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
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-08-02 13:39:36 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-08-02 13:39:36 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-08-02 13:39:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-08-02 13:39:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,# teardown
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
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
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
,ok 796 should be 200
ok 797 should be equal
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
,ok 851 All tests passed!
,# teardown
,2017-08-02 13:40:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-08-02 13:40:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-08-02 13:40:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-08-02 13:40:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
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
,2017-08-02 13:40:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
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
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'listening 49875'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57A9FCF1-AB81-4433-BBB3-0B6005506F6D
[ThaliCore] Browser.startListening
2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B62FD9DD-B264-4CBF-8735-F2F333E048E2
,2017-08-02 13:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
2017-08-02 13:40:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","generation":0}]'
2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for DBD8E41B-2745-45AA-9AFC-91E8212BCF42 (syncValue: 2)'
2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DBD8E41B-2745-45AA,-9AFC-91E8212BCF42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DBD8E41B-2745-45AA-9AFC-91E8212BCF42", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:,notConnected:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}]'
2017-08-02 13:40:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}'
,2017-08-02 13:40:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B62FD9DD-B264-4CBF-8735-F2F333E048E2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Advertiser: session connected Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Adver,tiser: session connected Peer(uuid: "B62FD9DD-B264-4CBF-8735-F2F333E048E2", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DBD8E41B-2745-45AA-,9AFC-91E8212BCF42", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49880
2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConne,ctResolved: {"syncValue":"2","error":null,"portNumber":49880}'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2D5A4CED-5489-48C5-AAA0-5C484A196223 (syncValue: 3)'
,2017-08-02 13:40:27 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 3, 5, 9, 10, 13, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 3, 5, 9, 10, 13, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPLis,tener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 3, 5, 9, 10, 13, 24]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 3, 5, 9, 10, 13, 24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [1, 3, 5, 9, 10, 13, 25]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 3, 5, 9, 10, 13, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:40:28 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 3, 5, 9, 10, 13, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 31]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 35]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disc,onnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DBD8E41B-2745-45AA-9AFC-91E8212BCF42:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,2017-08-02 13:40:29 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34]
,[ThaliCore] Session.session(_:peer:didChange:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49898
,2017-08-02 13:40:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":49898}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 37]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 37, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:37 [1, 3, 5, 9, 10, 13, 25, 26, 27, 28, 29, 30, 32, 34, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 3, 5, 9, 10, 13, 25, 27, 28, 29, 30, 32, 34, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCl,ient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 3, 5, 9, 10, 13, 25, 28, 29, 30, 32, 34, 39]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 3, 5, 9, 10, 13, 25, 28, 30, 32, 34, 39]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [1, 3, 5, 9, 10, 13, 25, 28, 30, 34, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 3, 5, 9, 10, 13, 25, 28, 30, 34, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 3, 5, 9, 10, 13, 25, 30, 34, 39, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:30 [1, 3, 5, 9, 10, 13, 25, 34, 39, 40]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:34 [1, 3, 5, 9, 10, 13, 25, 39, 40]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,1 [1, 3, 5, 9, 10, 13, 25, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-08-02 13:40:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 3, 5, 9, 10, 13, 25, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 3, 5, 9, 10, 13, 25, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [1, 3, 5, 9, 10, 13, 25, 39, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [1, 3, 5, 9, 10, 13, 25, 39, 40, 41, 42, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,2017-08-02 13:40:32 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket clos,ed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDi,sconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:42
2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
[ThaliCo,re] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalize,2017-08-02 13:40:32 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,dDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:39 [1, ,3, 5, 9, 10, 13, 25, 40, 41, 42, 43, 44, 45]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 3, 5, 9, 10, 13, 25, 40, 41, 43, 44, 45]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [1, 3, 5, 9, 10, 13, 25, 40, 41, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [1, 3, 5, 9, 10, 13, 25, 40, 41, 43, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [1, 3, 5, 9, 10, 13, 25, 40, 41, 43, 45]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [1, 3, 5, 9, 10, 13, 25, 41, 43, 45]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore], VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 3, 5, 9, 10, 13, 25, 43, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [1, 3, 5, 9, 10, 13, 25, 43]
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [1, 3, 5, 9, 10, 13, 25]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B62FD9DD-B264-4CBF-8735-F2F333E048E2
2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-02 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DBD8E41B-2745-45AA-9AFC-91E8212BCF42","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddre,ssPort":null}'
2017-08-02 13:40:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":nu,ll}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:40:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:40:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:40:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 865 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'listening 49908'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5A64512-996D-4760-894C-603F43EE5BA7
[ThaliCore] Browser.startListening
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE
,2017-08-02 13:40:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
2017-08-02 13:40:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}]'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 2D5A4CED-5489-48C5-AAA0-5C484A196223 (syncValue: 4)'
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5A4CED-5489-48C5,-AAA0-5C484A196223", generation: 0) found active relay
2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":49898}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [1, 3, 5, 9, 10, 13, 25, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [1, 3, 5, 9, 10, 13, 25]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-02 13:40:35 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2D5A4CED-5489-48C5-AAA0-5C484A196223 (syncValue: 5)'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0) found active relay
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":49898}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
[ThaliCore] Brow,serManager.foundPeerHandler peer:Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","generation":0}]'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","generation":0}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [1, 3, 5, 9, 10, 13, 25, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [1, 3, 5, 9, 10, 13, 25]
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29 (syncValue: 6)'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [1, 3, 5, 9, 10, 13, 25, 49]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHa,ndler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
,2017-08-02 13:40:35 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","generation":0}]'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","generation":0}'
,2017-08-02 13:40:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-02 13:40:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [1, 3, 5, 9, 10, 13, 25, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [1, 3, 5, 9, 10, 13, 25, 49]
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Advertiser: session connected Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49898
[ThaliCore] Session.disconnect() peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2D5A4CED-5489-48C5-AAA0-5C484A196223:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0) relay removed
2017-08-02 13:40:37 - DEBUG thaliMobileNativeWrapper: ',Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}]'
2017-08-02 13:40:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with, {"peerAvailable":false,"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","generation":0}'
,2017-08-02 13:40:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-02 13:40:37 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D5A4CED-5489-48C5-AAA0-5C484A196223","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02 13:40:37 - WARN thaliNotificationClient: 'peer is not avai,lable'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49917
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":49917}'
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 26AD2EE6-305B-44CC-A33E-0510D7802E5F (syncValue: 7)'
,2017-08-02 13:40:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [1, 3, 5, 9, 10, 13, 25, 49, 51]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11 state: connecting -> connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [1, 3, 5, 9, 10, 13, 25, 49]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [1, 3, 5, 9, 10, 13, 25, 49, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
,[ThaliCore] Session.startOutputStream(with:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [1, 3, 5, 9, 10, 13, 25, 49, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Advertiser: session connected Peer(uuid: "5891A3EE-D937-4353-ACE3-CA5B2BF22CDE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,53
[ThaliCore] VirtualSocket.deinit vsID:53 [1, 3, 5, 9, 10, 13, 25, 49, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Thali,Core] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA27E11
[ThaliCore] Session.startOutputStream(with:) peer:9FB72528-4FE6-478B-9FE5-2FCD0CA2,7E11
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [1, 3, 5, 9, 10, 13, 25, 49, 52, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-02 13:40:38 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-02 13:40:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 866 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [1, 3, 5, 9, 10, 13, 25, 49, 54]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [1, 3, 5, 9, 10, 13, 25, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
,[ThaliCore] Session.session(_:peer:didChange:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "26AD2EE6-305B-44CC-A33E-0510D7802E5F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport,:49924
,[ThaliCore] Session.session(_:peer:didChange:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A state: connecting -> connected
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":49924}'
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2D5A4CED-5489-48C5-AAA0-5C484A196223 (syncValue: 8)'
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D5A4CED-5489-48C5-AAA0-5C484A196223", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
,[ThaliCore] Session.startOutputStream(with:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [1, 3, 5, 9, 10, 13, 25, 49, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,6 [1, 3, 5, 9, 10, 13, 25, 49, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2,DC-45AC-948D-7A1ABD41B9E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [1, 3, 5, 9, 10, 13, 25, 49, 55, 56, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:comple,tion:) error:peerIsUnavailable
,2017-08-02 13:40:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":"Peer is unavailable","portNumber":null}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [1, 3, 5, 9, 10, 13, 25, 49, 55, 57]
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] Advertiser,Relay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler d,isconnecting:false
2017-08-02 13:40:41 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [1, 3, 5, 9, 10, 13, 25, 49, 55]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [1, 3, 5, 9, 10, 13, 25, 49, 55, 58]
[ThaliCore] BrowserRelay.didOpenVirtualSocketS,treamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [1, 3, 5, 9, 10, 13, 25, 49, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDiscon,nect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] Session.startOutputStream(with:) peer:14CDD1DD-E264-45D9-847A-348E1B79446A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [1, 3, 5, 9, 10, 13, 25, 49, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [1, 3, 5, 9, 10, 13, 25, 49, 59]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26AD2EE6-305B-44CC-A33E-0510D7802E5F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [1, 3, 5, 9, 10, 13, 25, 49, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
[ThaliCore] Session.startOutputStream(with:) peer:84EBA22C-7CFD-4B2E-A071-1E6274AF0B70
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [1, 3, 5, 9, 10, 13, 25, 49, 59, 60, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain C,ode=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler removed virtual socket vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [1, 3, 5, 9, 10, 13, 25, 49, 60, 61]
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] Session.startOutputStream(with:) peer:20A96530-E2DC-45AC-948D-7A1ABD41B9E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [1, 3, 5, 9, 10, 13, 25, 49, 60, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
,[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [1, 3, 5, 9, 10, 13, 25, 49, 60, 61]
,2017-08-02 13:40:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-08-02 13:40:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 867 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5891A3EE-D937-4353-ACE3-CA5B2BF22CDE
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E7FE4C83-AA88-4B5F-8AFC-024A3E3E0A29","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-02, 13:40:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"26AD2EE6-305B-44CC-A33E-0510D7802E5F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-08-02 13:40:42 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:40:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 868 passed
,# teardown
,# setup
,# compareBufferArrays
,ok 869 should throw
ok 870 should throw
ok 871 (unnamed assert)
ok 872 (unnamed assert)
ok 873 (unnamed assert)
ok 874 (unnamed assert)
ok 875 (unnamed assert)
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
,ok 880 should be equal
,ok 881 should throw
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
ok 910 stop after start
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
ok 946 verify failed
ok 947 constructor called once
,ok 948 constructor called with right args
ok 949 start before stop
ok 950 We got at least 3 calls to start
ok 951 at least 3
ok 952 default 1
ok 953 1 run
ok 954 default 2
ok 955 2 run
ok 956 default 3
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
,ok 971 constructor called once
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
    at module.exports@/private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/B,12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/B12823E3-,F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
    at module.exports@/private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/B12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/B,12823E3-F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/B12823E3-,F20C-4B06-A060-50C32DD02D23/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'listening 50002'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:12CB1BEB-CB96-470F-AD4B-6EA9FC7B3CF5
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EAFDC811-D504-4FD6-946C-667BB6B3C6B4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EAFDC811-D504-4FD6-946C-667BB6B3C6B4
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:20 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
[ThaliCore] Advertiser.stopAdvertising() peerID:EAFDC811-D504-4FD6-946C-667BB6B3C6B4
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-02 13:41:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-02 13:41:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-02 13:41:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 50004'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F54A3D5-F1EE-468E-BA4C-C6D345C77736
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F0A4901B-0F6D-4DFF-BD9C-AEE8D99F6FEC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F0A4901B-0F6D-4DFF-BD9C-AEE8D99F6FEC
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
[ThaliCore] Advertiser.stopAdvertising() peerID:F0A4901B-0F6D-4DFF-BD9C-AEE8D99F6FEC
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
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
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 50006'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFEACC65-00EE-458B-BC7B-17C74EEF0065
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5EA6B4BB-EA00-4507-86BB-F0891CEDCA25", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5EA6B4BB-EA00-4507-86BB-F0891CEDCA25
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5EA6B4BB-EA00-4507-86BB-F0891CEDCA25
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
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-08-02 13:41:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 50008'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA1F483F-6328-4948-9419-062F97FBF959
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B6CABD73-35AB-4979-9FEB-47CF9E06CE16", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B6CABD73-35AB-4979-9FEB-47CF9E06CE16
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B6CABD73-35AB-4979-9FEB-47CF9E06CE16
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'listening 50010'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8EA4825E-1A29-484F-AA05-7E2CF25EFE91
,[ThaliCore] Browser.startListening
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-02 13:41:21 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2B01CF99-F387-4423-AFBE-5F1EBF1A00AC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2B01CF99-F387-4423-AFBE-5F1EBF1A00AC
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
[ThaliCore] Advertiser.stopAdvertising() peerID:2B01CF99-F387-4423-AFBE-5F1EBF1A00AC
,2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-02 13:41:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-08-02 13:41:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-02 13:41:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
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
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
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
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - start and stop and start and stop'
2017-08-02 13:41:23 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - two identical starts in a row'
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
,2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: 'all tests succeed'
,2017-08-02 13:41:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
