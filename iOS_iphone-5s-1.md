#### Test 113351851d000154_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/7E3D3D42-7AE1-444C-99A7-CD170A295F77/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7E3D3D42-7AE1-444C-99A7-CD170A295F77/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851d000154/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57400"
,(lldb)     command script import "/tmp/7E3D3D42-7AE1-444C-99A7-CD170A295F77/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB5C1C67-5472-458D-B23D-5FEA7EB6E3B6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BB5C1C67-5472-458D-B23D-5FEA7EB6E3B6
Optional(tru,e)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:308A4EA1-73FF-4A6B-ADC6-7CF1AD0198AE
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:614F3E75-,CE2D-418D-BF15-B0EF7CB3F963
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C258B178-48D3-488F-9238-8F91D3D8E1C6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C258B178-48D3-488F-9238-8F91D3D8E1C6
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C258B178-48D3-488F-9238-8F91D3D8E1C6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C258B178-48D3-488F-9238-8F91D3D8E1C6", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 07:56:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.800367951393127
,2017-07-21 07:56:05 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-21 07:56:05 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C258B178-48D3-488F-9238-8F91D3D8E1C6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C258B178-48D3-488F-9238-8F91D3D8E1C6", generation: 0)
,2017-07-21 07:56:09 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 07:56:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 07:56:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 07:56:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 07:56:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 07:56:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 07:56:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 07:56:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 07:56:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 07:56:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 07:56:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 07:56:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 07:56:13 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 07:56:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 07:56:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 07:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 07:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
2017-07-21 07:56:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
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
,ok 29 firstPromise - in then
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
,ok 51 participant data matches
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
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 07:56:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:56:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B9E9BA8-261F-4AD9-8E82-E9F094B277DB
[ThaliCore] Browser.startListening
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1AF7371F-4847-4B29-B576-9B65D4533914
[ThaliCore] Browser.startListening
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:44 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5AE3B1F7-B2D8-4CC0-8CEC-B49DB24B49B5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5AE3B1F7-B2D8-4CC0-8CEC-B49DB24B49B5
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:5AE3B1F7-B2D8-4CC0-8CEC-B49DB24B49B5
,2017-07-21 07:56:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5
[ThaliCore] Advertiser.stopAdvertising() peerID:ABC50CD9-048A-441B-9CDE-DC7AFD72FCF5,
2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:56:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:56:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6F4D58C6-50EC-4889-A6E2-79C7E140AF34", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6F4D58C6-50EC-4889-A6E2-79C7E140AF34
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:48, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:29A6063D-8D08-4AAB-8F02-5423E21872B8
[ThaliCore] Browser.startListening
2017-07-21 07:56:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advert,isingActive":true}'
2017-07-21 07:56:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"route,r":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,ok 76 peers must be an array
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C21BA560-FF4E-445D-9B31-8D16DD9BA945:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C21BA560-FF4E-445D-9B31-8D16DD9BA945", generation,: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6F4D58C6-50EC-4889-A6E2-79C7E140AF34
,2017-07-21 07:56:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:56:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:22B764CD-1CCE-4DBA-91F5-A067A3B0164D
2017-07-21 0,7:56:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16864A41-D630-45C1-B0AF-4E67A4AC8C31
[ThaliCore] Browser.startListening
2017-07-21 07:56:50 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:56:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:56:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListe,ningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF (syncValue: bADzu2e0Pgf2fsL9HOfjTNfRCpbRZ82s)'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","generation":0}'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
2017-07-21 07:56:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","generation":0}'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:56:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22B764CD-1CCE-4DBA-91F5-A067A3B0164D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit, ,peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CD,6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,D6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bADzu2e0Pgf2fsL9HOfjTNfRCpbRZ82s","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bADzu2e0Pgf2fsL9HOfjTNfRCpbRZ82s', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:56:59 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBC,F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:56:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DB06BF0-3361-4720-9B4B-E8F6A5B37989 (syncValue: rtgdn1GvHtxT2PlEQz1OmUX,HMIUJ1xfg)'
2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DB06BF0-3361-4720-9B4B-E8F6A,5B37989:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:56:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CD6697C3-80A5-4BF6-8ACF-DDFD13E1FBCF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4
[ThaliCore] Advertiser: session connected Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56768
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4
2017-07-21 07:57:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rtgdn1GvHtxT2PlEQz1OmUXHMIUJ1xfg","error,":null,"portNumber":56768}'
2017-07-21 07:57:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rtgdn1GvHtxT2PlEQz1OmUXHMIUJ1xfg', error: 'null', listeningPort: '56768''
,2017-07-21 07:57:02 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4 state: connecting -> connected
,ok 85 listening port should not be 0
,# teardown
,2017-07-21 07:57:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:22B764CD-1CCE-4DBA-91F5-A067A3B0164D
2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07,:,57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56768
[ThaliCore] Session.disconnect() p,eer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3297E131-DDDB-48D9-8747-F6AA1CD08F8F
,2017-07-21 07:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser,.init(serviceType:foundPeer:lostPeer:) peer:1BC6CF72-92DF-41DB-A614-902FBC0128D2
[ThaliCore] Browser.startListening
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4 state: connected -> notConnected
,2017-07-21 07:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:57:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "22B764CD-1CCE-4DBA-91F5-A067A3B0164D", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,ok 87 Can call startListeningForAdvertisements without error
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:F8527CE8-7E0E-46C7-8476-2D0D47B99EA4
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1DB06BF0-3361-4720-9B4B-E8F6A5B37989 (syncValue: d5BCYzW9nagPS12VFRmakzNjC943UIwI)'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","generation":0}'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
2017-07-21 07:57:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","generation":0}'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3297E131-DDDB-48D9-8747-F6AA1CD08F8F:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","generation":0}'
2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1D,B06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1DB06BF0-3361-4720-9B4B-E8F6A5B37989", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"d5BCYzW9nagPS12VFRmakzNjC943UIwI","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd5BCYzW9nagPS12VFRmakzNjC943UIwI', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1DB06BF0-3361-4720-9B4B-E8F6A5B37989","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 26D99AE4-FD01-4D89-8824-8246C4432DC5 (syncValue: eocGlmfo5FA0Mg6p62lN8F2,1dgDfJdTk)'
2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26D99AE4-FD01-4D89-8824-8246C,4432DC5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1DB06BF0-3361-4720-9B4B-E8F6A5B37989:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:26,D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,6D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:26,D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,6D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "26D99AE4-FD01-4D89-8824-8246C4432DC5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eocGlmfo5FA0Mg6p62lN8F21dgDfJdTk","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eocGlmfo5FA0Mg6p62lN8F21dgDfJdTk', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"26D99AE4-FD01-4D89-8824-8246C4432DC5","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 44B8682C-03C2-4208-8FBD-AE9D3CBB179E (syncValue: k5QIt2q6YykaLlxzhML9my0,XBGaK99Uq)'
2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3,CBB179E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:26D99AE4-FD01-4D89-8824-8246C4432DC5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA
[ThaliCore] Advertiser: session connected Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56779
2017-07-21 07:57:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k5QIt2q6YykaLlxzhML9my0XBGaK99Uq",,"error":null,"portNumber":56779}'
,2017-07-21 07:57:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'k5QIt2q6YykaLlxzhML9my0XBGaK99Uq', error: 'null', listeningPort: '56779''
,Connecting to the localhost:56779
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,Connected to the localhost:56779
,2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 07:57:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA
[ThaliCore] Session.startOutputStream(with:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 07:57:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45
[ThaliCore] Advertiser: session connected Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45
,[ThaliCore] Session.session(_:peer:didChange:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45
[ThaliCore] Session.startOutputStream(with:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-21 07:57:26 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3297E131-DDDB-48D9-8747-F6AA1CD08F8F
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56779
[ThaliCore] Session.disconnect() peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:976B9A94-5517-42A1-8030-647CBF5D1D45 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:976B9A94-5517-42A1-8030-647CBF5D1D45
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6B1FA896-089E-47F1-A059-7B78FA7385CA state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "3297E131-DDDB-48D9-8747-F6AA1CD08F8F", generation: 0)
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18629558-6C03-4C79-916D-F3DF313B891E
2017-07-21 0,7:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17A86F4E-6594-45A6-B9F9-195D16166C20
,[ThaliCore] Browser.startListening
,2017-07-21 07:57:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:57:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:57:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:976B9A94-5517-42A1-8030-647CBF5D1D45
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
2017-07-21 07:57:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","generation":0}'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 387EC95F-5F42-4F46-A25B-FFFA6275C91A, (syncValue: 8p7AMn57IHnNHAw9Oi7nl1Cckey1O2HV)'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA627,5C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
2017-07-21 07:57:28, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","generation":0}'
2017-07-21 07:57:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:28 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18629558-6C03-4C79-916D-F3DF313B891E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
2017-07-21 07:57:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C67E6215-DEE9-4444-A445-F329D8DE911F","generation":0}'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","generation":0}'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:38,7EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,87EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "387EC95F-5F42-4F46-A25B-FFFA6275C91A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:57:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8p7AMn57IHnNHAw9Oi7nl1Cckey1O2HV","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8p7AMn57IHnNHAw9Oi7nl1Cckey1O2HV', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:57:37 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"387EC95F-5F42-4F46-A25B-FFFA6275C91A","peerAvailable":true,"portNumber":null,"recreated,":true}'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:57:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 44B8682C-03C2-4208-8FBD-AE9D3CBB179E (syncValue: I5n0yjyouXDJpkQCy0BKjRr,YANtRwOBq)'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3,CBB179E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:57:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:387EC95F-5F42-4F46-A25B-FFFA6275C91A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
[ThaliCore] Advertiser: session connected Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,4B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
,[ThaliCore] Session.session(_:peer:didChange:) peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:44,B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "44B8682C-03C2-4208-8FBD-AE9D3CBB179E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"I5n0yjyouXDJpkQCy0BKjRrYANtRwOBq","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'I5n0yjyouXDJpkQCy0BKjRrYANtRwOBq', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"44B8682C-03C2-4208-8FBD-AE9D3CBB179E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:57:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C67E6215-DEE9-4444-A445-F329D8DE911F (syncValue: mEqK5PPv6lziVtZBvLPAuDl44ovf1L3s)'
,2017-07-21 07:57:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:57:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:44B8682C-03C2-4208-8FBD-AE9D3CBB179E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
[ThaliCore] Session.startOutputStream(with:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
,[ThaliCore] Session.startOutputStream(with:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
[ThaliCore] Session.startOutputStream(with:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0 state: notConnected -> connecting
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017,-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received all data: rIL9tuOnoxbLb1UNxrRo1B7O0YyFIjRJJMfPDgeyqhfUiHwCIyiCDEGOpSOeEjMQKDtCXSryDxHuzOqfsttZ4f86bBkQ6fl17Y2jxVq8s97DINyOMLXHjEv6vOkDXfdDk9ii8Pb9ukrRCOBtAzUzTEiDFlr6X7DK6u6pGLWTMQClk7fcPP1B3S1ucB7wMloE1bRvlW3ho99vEbBq5cq0I2CQGUnGYCEEZUSl8ENcVdxEApX1dihE7K8ZakFKQxN6ODjukKdegxNGEokLwOwLGD4YVjHGgoZf4v1d30vS9U1Z9NwqgZr8F6d356JgPsoQnSLjWyfewXxUAo2y5Gx2oVF5mjg8M4NUIZbNU7bTUeCB9ZeqKsFYq20GSVEsK5ISEfMzN2nlvFmlXEPlEeoh8SZok9ksdetRcgk8ffBPVtVg2smxxV3fwiKgr8rdu0tVD5PA3j99TTFzluicEVfW0kYrDKL340jW4xLVBA0s1PyrfHuwttqg2WskjGTEYP9lOfsuBN7uyDQOXNYWURNdltrluLchTpIN36r6qV15QOC3r79Usnr92bkTEySYNQMrPGnE3uNfjVq4A8CRvsVSSk6Z3HTik76I5tYFlUj9Lo9cF8SjVeyXPoOzqhxueekGUfLERN3yK3YGtmpHiypw4HE8UrBKltDplBjh1bmFGIrP1zCR2U,l6uWhei3qicyWfSP63DjcQGO9Lm4KigzcUsR8DiKh2J9lHq84wff3JxKORTwiCoqyvU8JbfPNjuZRcXhTYqTo0h3zE9dRfhp6loLH0dM4oPv14kPfDpoljqwBm2UgybWdvEwRlacTt52p1iJWIce10R7vZC1w1OmymJVyWt4UyM3Na6oA7IGrKylUoSXjKywOGZzaPc2fxNdq7dDyen9vvrWYPKfmAy5GZaCtXIfrTJNCr0TfWsNsFbK7ieWhvg9,PJxvsIA6F7Q9p8oDOo1wDKy7McKhm2fNqARAEvtDiUEvqnoHpfKJXpTndloFPklcSywYleAgbxcjUFn2MfendundFsrsFBpQ4Y759K70OGPcN1NpIS3cXYFa0PNjtLMWdjGq4PQLvjreyDT3h9Kqge1gFrYzKoioumqrEh7Ib2l85As9DEfWMwucRUmjohBvB5YDWGHnlfGyRBnUdF1EB2iClO0vDIyCOrLYIYdjBT3gaZLMV2YX6UGoR3xfBdau,vhei3qbsAPJIUygUhk1je1I89bw7tiUFiv6CPJH04VKrPZU9vMts0yaXm5gUmIyZim1WBzWcD3L3M0LG0T6WYRdWtaj7zYSu22E9WXmBZpfT67SIYyWX1DFVODi51sUJXFQ7IVsff0uMT4MBtEvFiEiZu7BzGhXqooJP5o3uCRDPEQ5oF51dZjmFqVve5kqZv3zhAiUOi50e1fB6j2WvdUWNNfpbCSPDSnKBksb6FDB3qSXWi0vxIKfClcOhLePX,jLMdXcUwE42J0OEkGZXh038uhBGWeLluS3V5ID7dPjspXtu5uG5QCFr7sWJtfRyVSc4aYFEAF4jhVIrtAB1RbniXvQFfgSgAuX0LQJPKYpUjpsLDiD9hZ7SeWOAaQX3UFN2UnxhiZ9uB53yTv8GnNYgVo52hJfGAhqEDE93o1Fm1aLj91r13kVgtPoI5uhsYPldJgzwmHofI3ZOfomBsC8pzEAjTe4vFOZOgFCekPlIai9ktO6TX5SJzIJL9LnnQ,rq3wa0ZlmdE9esC4pA3UtrGtH6zygj3M6uuQnWTAKwC50TJHlnWqiYxfEKSQCssrJ0GWJ65UGXrVEYhbzlzivnH6OIU35AHp65zeAUHThJ36rpBxQE9MOs4ZkS8Hokzi0DNP2MV2IuQaYveh2OJkzqaPoy13gbG9S9YHVx7N5SPwI1PVY1uRMYX8lzCvu34ZzFiCFQK6A2pfITKDsEwzpmFqwjMbd26hl30j22TH7atBudU2NiWGT05spUoBjyY,4,l2YOznx6CuzUJnJ7g5vTs05otJUJPmiuUJFiwpYJ4aEuBNE5YLBiFp8wOGbskLlCwPUheheH3JSq61V25PCzxb01ps0UtXHQ28xiZ2F0yZ7UoIyVTu8S0Wwbkadg6XuCiOV2ugp5pSFy6YNX4rqg2v9KpxJD3kuMh2cTYHwLQGWgKKkeI5glQPu5LvPf6FAZmItQbMkZVF2m1JqEERs6UFFiHDKYJtgaeNzCGCCCKyc48jPk3dMz2BQemXow6u58,ERAuLVwHkgCm2gcNlZSkVJ30vaJMYlzhLdF0148FR7yWfrys1mOYSECwRuKS9onGHOZcSQHIQRtQJUYh70lkEM0e0ZNr1kfp7S2XP2OmBTZ84fFSSPedtEZue1eShhPKavb1KXjUQhlKT9i8NUw6zYB2SgnuAXY6exfSY9DwoDuEpycN7qOTsfEmV1qBtG7FteIOQpWLHNsTqwL51cvLJFUr3Ex5bm6sZ3fQhutgno1Msojdny7MeDB3xtEFxG7aCxTjgPFxuLN08BGMAICukT7QBUCvpcXpEOX1WsyrgJK0dWElE3qVBqZrUkNoWaXcjFdM745BD3qOdYdpTcU7uCrzvX7IiU9zwcXSOPU1G4hXR2jkhfvcjMMoaFKIHVNaUMVil5ExrokWpufhTWXg1S4BeWGz4GzWill2PDsVMz1Xgk2SUZgbhFrOZ0ZRknX2mEFnM9K3gnVZDYxQP6OAVeFTUo4vV3StYeTAcUGl8iOes3vhYbfq2p90X85vei4I,l3PHaGeScBPdzmH9cNI1FS89PYe9VlwKu3oIe5BbsFbYolJtpJ1fp7B3JvZMJe11FhTnO4JcdYico8vlym8fDC1o7P70x6wBb062GIv7Jxj9OkgW4moFr9eob1tEzhMCxNcN77YShL5vQ2HiuBbxg4Iz4Wi4HuSdOzMwefUiP5ip5YYD2G2AxqnRvdy7CLSqEHfwQhiaklikwoJYzucARI0uA1pNUaQMuhax25pNEzxY0s8cL7tWnaVaNNDOhWj,y,YBPyQjsSEhCBSYewk0R5NrNMwCViIqZHy08jN3zPNqizbgkRfiGCaftefDHFtLBwco3mc4KLSb2OqJxwy5WqPgzVmVa2Pc512qT81YbCa2NBZ1k6mt9c54ewCKEn5WPsUH2C6qLJx1ZxNwqRNb4oaPXtkRQEYrSu7ADf8ASxsWNNz5qWGryoNXn31jDZXvsau023aaZH4Kh55CvbbceTztuIr1E95snyx8au0nM4Baj3NYwrw1PWCs328rQiYKAM,O9JyHV6ftzWPSwbQI8tjDacVC3lENySJLr9wFgjlDC229nnKDUzYElX5Xb08alHgzVEJNu4ZMDnkZqardeGsgnHBFT5E8uJHL4l9yGfSoKVvCJ6GK7w4QjoQI5oebz1BGM8zo82NeyfL0swLzruKc2vfNZr25FbCidj48uyEkBIfTOhdQYt6rw9cYt55H1Skmyw7Ax3PfwbBIKYZVzVIH6tEOufarsveH8Fm4frKG6wbQzDvDoVoG08V1KIfPw0t,ymHkxGBkyR7bTn3ZYW1j1D8gww7onQx19RGoORKmAafAVbIQ1NEvK8BpbTNy79PsFkiH7GNqv1XmJ1ZtkXmVEal191Vo2ahH9eQFYUAsCR4wz4gYvNal1molGyHxvgWTg9GFHIJKTopBFMdypiC8FYqRHydU98zTZw5xN7zgFTut61KjOsGy0eynR9gBW8lv6rchtkPjJYVVgtomlO8c2m4Dq2W4ZHnwHDjz56WMwuBru93O1UBU9XxesZe0bwYs,ZWn5K5uu3SMMfC8Zz8mPvbQLP61ry58QAuYh2xJ69CUGoxkw09bifoiJkcQVEXwi57jjEKfXjnCFmUekAz3OJp3qX0vu1dHn0nW2FK40CuCGHKSEat7vsJliwffVixxv129zmCIoirXUbLR73XroqtjD77YVSb854FcVdnOOFEFXlyrg1mGHRptVNFW61GbZ3whWxYGxXedvMdtlHY1G8IUCINtcJL15pVsV1Sq55Jd9XCVyp2KBOHIdZh7bUnp,b,pUZI7siILnMzv1s7onnZF8W7YqaXT9Yu1zSOOLVQWeAJZn1c1rq6wgTD5YIB1NLcZqyXWAQwD66U4mhBMdfqzfucNS7Si8pT9rZ1lDtPQgpqFaHWjLbaYHp7yoZgApIg6szQUyo20OM4Nt6XnKXrswthQeKtO95lF7Ti6tFfzO6bwRY20ZsxdeeKUt9wi4oztyExyyGGlGKXTz23ZojJT6zlYGw29vZtOPYXvVdGLwzIyVNGLEnvYpOEXdyeuVeXli2SM2w6H5nXINvOGUBr0wkodk8FzWmqIMZNvgCBqOTNdRnqjwpGXPYqjg3MuhY39vuRU053zzm9o7yKjKNC7eWZqOwKYvCcVhWh5wtxqmSMifhpjUNkgJBUvL2MCNZEGEyAgeclyky172iUhXWKJhm9g1vyb5fUmXMhmPWiwTPZCsaG8PPqxBJ3N2kvIWs7TJkJh1wjExjFY8o6VGVSM64j3r46Hm9JAesaNv1qiwkuNyUjN6zVymTdPIqSoXBM,LFoDKzpa8tktPugSXtzdthetkrocDCF53Ym3aMdVYY8Oaw6uhzG6Yyk9hWLlz4cuAjDodsH51UPeyA4uzhNwd4dZVsdaUMNyPBpItYhm9TFfT680KHG7WB9DThmrIpVhKOlgF3I7tRwBeikrMw4qDkOI9ddP2yFVzC1SCOz3PvStLu4ir65hginnF2eMldcVvUOgIPb61DjCOFzxl4vfKAPngvY0Sj0tdJ6GtGFoFQ1NEa7HHZnPYBL2QUQcwwS4,Oa4WA9XOA8gJhagXXwbvhC1czrqgIWP1pRRiun0NIO9N1XYRK5ayfNrtvW9x9L1zwBLQ8F1w6gqhZkuJNQp4ZUJR1KrwEGQu8jDKWwnTEGGRl7731vZv7PHWSfu6UUIqQGfrkYiHBZxmdmelhqdNf3fBIdU7egTPnqZ9SZhay5OJS2rbcsKG00iuyi1DTJ63Ksyn7Ca0PC7lqAQApsNmodNU1tO8xSvRXkmLX9ckKYQjCJgylhzYN42U3kz46hG,e,iQgX0qwnkNxWM4pyGd5r0NQGiInipI1eorHqrGdtaclh8k972YetPEc4c556QcBQJ48siWIEC9qCBFkrpIeStCUNtaPdD385QG29p2GgCiJljPgtio4f0Bfj9Cv8BeJeUgi1KSEmTflOqeSJISHT3GSK6f5wof46poEepXS3zDJj6fN7z6a7OO8f7n4ODvZwmDV5ZtWPxevOfdDWwqCtLDebAj2llDEcYDe6LJ6prDHc2BHcOwhMqbwEiAHbfcjs,8P8vfV22E8NtsEQt0xQHHRy98RO001SyNWwWdBiwLVZkJ2MyasnfpmKbHPCnoZBv9N8bUjqAeVXyDSz5IabmI7j75yh5wtNjgBgXJ1ZyLGhuRBiz7ORho7ienDhi7PGNFUgmRWPGWxk4ziNKTsPEyfrpTqO9BDRdWsMRjU5FUouZjDYqSVGbnlBsYAyYdq81QoxIjuTDVX7lTKTEKLV2TQd6SQTjFYVH9mAFwcGJv6IpfjYogVlr0Job3lSrQaoO,vgpts1HP416lVgp0foNpH0rlWRINt6PdqeGTfO0l8LRg30NWfLkongNRUjZJph5FZPwgCIB3bfadJ4S9WuxWjRJE7yqcKjCVE0cJqqHa4S82lPNs1zjr5uXoPoWzKUZ5xhPdmDThriGlgHR2u3RwYgBIriBTHzF8dUyA5bYFJO50ZDV8bMmTmpfEfGX3wxqb57vGEvrQsIiOrEmVuEyRbaB1brUfv5oRfkHXCqLv9Lyi9j0atnHR1nKsAyUuojrq,IR2jBMBUTrcGhCS8qgdGQhC8jjWDFDLJwMNRu72qVT7pBeKRr5tvsHYnDY2AurErqpE9pFoBVyc1i6HeuQ88BWLTCCaJ4v4ebW1QGJQzxGiOFRjEgwgdRoN6f7hzwvjIIJdUldhpNhDPpjPzJkMZGOOtc6BWmSiOKfqeAxZDVCOtcJfUuN4ZAlvx4W3b8TGGJiEJzbHGQA9uzi8W4reAsu1boBq8xDe6BkbljyxTDGwqwgNh1rWHpTtiWKCyYbR,T,IWyAhiDicw3v9EYBiLjyFDmv3EYIYuAfuceA3YEH3rBc191B4aNmbI8L1NTriR1zSsxphqqskgokHCNQBoRauh9Y8oV3LGox7drRpMwNCBABcDs9g1gxedCIO2o6ZpilAeHFmTM9S4QU36JFyXLUlkYBlcLvTillmOc1WTi6TXUDx0QlXjdk34YbCMx9ad55nGDnJ3dbNRSKayuTm2XcRf7roxHGn1iDSgR2bFNHVHSprNe0Hhfvu2jcG1qK03Qs,7zHduK79fL828umbHocceUoJhnwvnYecV8XObcRd8sL1F7b2EHRzuMEZj4PXTxeRAJa849SsTCkcWdHy9I3uiBgCv8qV426xoffAhEXwut8ejTelhtyJA9ZJBIpgK1oa6xBBu1EcQ0wkK3ZhX7JoAMKVRwEklx4nX8D6REfVMRqeYkajXjqYaREXdCvbYS3K87ghyoyAIjVBH4A0aCieKmfUG82kfGx9q2jnZdJ05TqxQAblznPHa2av20Jn3sUJg52eMcV3mBLASOa7QyxNsS40xiQaWs2JkZdeGfIpflhxLiZeW6k1UQ8ZnxbDNUBoVIpLyVJ6A6ZK8EF3avervbq40jARA7T1GBoTcBS1udpInIvadKic3eIMUMGlVJ4EA3PVn3VQL9nACX29fiP4oI63vdEDNNW1WqcSadry5zE7oxgCQmC6NTKdP092DIdrrdKwQdH4I0HtevrKAUuoHPBlYUzhvjcYfNELuZCh13RlSDvzZRqjTU04jzcMhIUf,ZicKI8oXNYADtH1qGjZlTzW2BiDevs31rdKhwkhyoFYtXNU89ECRrbMkFuBkcfhQAAAWfyf3x1ESXXmxTIVwnTPDLt466Y0PLtoU9zjBenRsGuzB06BlLrs2J1Vrdgf0DAIjxWB2H6w6Npgi1YNYNtZEdHYbuWtbCDQiGh0xe14hayXQ9C28i8a6Kpnh6G7lWoRNSYFpPwcKgk1mheaFqfMFjPdOuY4rVzsglzhd39knLJ0nB3V6MUK5ptOFt5G,L,ygTgBZFBj1SR7nlkwn44SPAdJmNWHBDLEbYexTIOlawij4kpu13KMGjFMn2oY5j2BH7gzU5liOOgwgTHu1H28kRzDOQyiFHMRhX8oM8prdEEPdI3GyPlrmSq2AYcRnUihgLocV9dboMUzJBeqMY4H2P56cZNxvD59xWGbl14kZOViegYPeKAC7tgvZucsup7KBI84OkZraPvp86jRqR5wmndG17sUkusK7tuZzFVM4J6QcjeBT9bDX3w6rFMBvrciKZRG39aB5Srm9X7ziazzlxmVLp3s0wK3KXeosDx86oTmhDSLSu8pf1XUOmrhdg0tzqphkSE4wHVjyARc7aHgo7Db9UvEJSeOg5PYNIK5GaBUFSEcK0TJpfp2NVAMW6AYr6D7jbI3TwByuqHJwTTSC4ff6khqrFmathlYWlhOhLR2JbhdVWiPqGB99zI6EgR8cWS5gDipYfi9qPm7y5qPbYbD7gU2nSQH9jPoDxGzkPVYR8Ih3U2JXOI3uWtCc0D,5EIfRxcBqCVs3LeFxTInit7fwJdIrNnqlq5ZvXqfgIsf39dLskjOcEr1ahJmmjislhK35lK2WEGE3fzIIr9nnTVzhRVIYLPQ1kE3A1RloIIDEBRIry0eaVwZJYFJ9Ty8TAHtKvjAY23GxWfHCfTlTHvHoRjsl24YFldLEBx9ag7f3DxWKbr2zf71zvyhzZh7DUu4fZrOqsJZ9Kv7XWu6h3a4RCTXMv5tfZWkE5ZM6h3rzXt4EuOYdMUN95Qhd90QnLKZKW1SM1TPoKKx8U9g8YzihKxL0ieZRkALZTKILyIMlK7z1H1HWfSKEczqbD2CYib01KpCXDd8OXkJUkF0VP8uEaDelCZIkJ75C2DmN1u5fYxGoQUYmOFHwom0QmQH9q3oMkz5AAHGnAvOSaAAfZM95uUUHnyASQRRWUHq35ofUpFYbvyfINcdZJeqtUcOeS8xGJQHwzaaeZlLF8UTWCHxn4ZDJQLBWRDBJFXE3A4ej4dtVpQekGsxJbCKybj,T,C0RB0HBGfJdttl46nL3uZvKDaXW88KIuOcpm5hpBz4OeNO4tNFTiHL7CTIqt8r2IWTDVH5qKzAl2fVlc27KkF2hcNyhpGwTGFV2uywikihazTgsYOzCPgoTCgzghLjzKERHSzd26puGCk0W7wq4Ls8Y5AkXcb71lRd4KAyLMaVg3ACLfpDRStgTEdm1N6oPzj5ef1AfqkKLQktynt07qZrcknq0dlkoYEuabqWpH2vUN1clx3SLhTc7ykKTfufAn,OPvh5qLg2r6lDAVBC712MIvS3c6SdUPf3B4LpCP0IgvoOQC4ujeCiBR8g1GfxBpmIl9AgxKfOxtphSFExfL52GplnLAtuL7UzwS9g06joYk9560IL9jk5wef4KbEdRa7rpaDWhyOBz6sOrFBB2U8p9NOHzaKwrJ9qsM7l7rjOFHhTpczk91n3Mq9jwxSodsKrIrmNa7T4sml5O99DqkxAYMRY3uDJuCOmwAgX2V4XTDlu2ZvFw1D13bKv7QLsnu8,TPa1H18kHWuequkmm2xXcer9inNQpN84rZTIaNFicLxDHhFDkKCHrw9CDPM4x6BklnkFW9M77PgY68mEn0ecGZbEFDGJsla7XZZX6D4OGXFMY9WlPTwNkqtM08LTjFOwO1RobUaiBh2Pg6ruWDCemLjVXMwa9my9gLrAZYwg6MqoC7uS45AG29QeCxz1zCZvHiStjtGzowwVzEzQr0BvcG5MSMEDlw7rO46lV23GwixPemyvREsz58E94MS5GzX5,ZwVLcm7xQ2JpxcoWaag3pZotRMUzMlr1lvnKxcZd4N4Bpzmrb5UHJJTGpz2M6Ol6z0L4Tza5x3ab5G0k1IDR2jr5vRDmMFW49PifdWV4MFwlcbQU1686Bk3HythzRCiGU6tuMw4wQ5GQ4BUnLrFXgnLxBnw4rTaqumu7SogIX0VujnrnY73oxgtSzzALTgyoo47fe2ykLo719bqdHvdr6SHqnvheDiDRG8eCpcs8G90Y7hT8E4sfIuC5ouSif1e,y,CajwGcG2A0v8TS1yQfNpFK7hFdkUOBQ6jfMJSvvAx5Xok4vK00l3KUATcrEUd8RFuYPsdPhEMorWAxM7iNCXngcdZ45rRwhqc3uGfL20Rver6KN5sKBXUU44TCsoAwSwmMevsSgMjGZKzMSdv82J2QiSijyNKjUzFN4YbXPUjcVAu0stktzNcoQmC1IRVW6VClFrDQiKUFEhbsu1xGEO0PuwnvrHp96vhS2SSuvXpOWi8IML8KcjxnbFqA4SjRrG,fKgCnsrO7au8Dgagn3qh26tNoEZwE2kUb1yjOxPXmRW3TMvLXGsBV8tlI5pxsDzBlYs4qHgFCyo4VPeo3Q1Msu7Aie8vuCPHpXR1Bd2rsxcsZ4EDpUAbtMtTPnAHAAbENzqT4WL5DOwxWa2khfYJOdy8pb3Ya5o414ZSqQWvHhOXsAZr5zfprIoNdpqZdL7thyF8M05qMyLPDoil5xRdAPVt0nEcyCZXG299QfJ4Ufc7NCU4IIKjSmzV7OCqWYakYaCZ59tGxiQSSjSbsQWmNpVuOaq4IsXLOjsJEcKE4U7GEb5l4AUnzGkmeX0dZ1ri7rUENQ6b4wxLwwYSVxleAp4wMFHejAUd2xLmftlJKvLRVVMQc6Ej5BusjZjIXb0ICcGnE5VKUhVrRa02wuaTVaUabB2xKDcY6Yn39bS0gHOSPz2Cm9GoATn0ONVN0n3IzdGgyOlH7tsAl8WqYiw4vfhYUl4ZMPgsiil0Q6O2ACGQ0J2gViMHfHGDH2ouerDbcEcV8fUh7RY141eCRM4PpcnJMg3Vq8Xu3gpa6rM22e7QU4h4mG9yjEt2ynwe2rmX9Mptp5P8uEI723JBtLGMW71P7quA2iy9prugoaATN9InWUV58I7KnhgeOgzKoAUWg9Aw9YGX7oY7uCqptI0wNs2RfJhHST6kNRMlzN7fQJPv6ALdJDm6B2ZjaZAGsJfZfwTjWrZyaSpS5cuTAFWUxJ43YdGYVxfWTIM9PzCV85AgnYjfrHbZpH0Y1PlENwH,e,AtL0L9zmQjPQh5cwUecuJIM8TREeyMYacimYB3tL3ersZwyW88BnqB4Acw6CUzYSPmJcmxtGBSj7ktbpeZYSLmLo3VuFUHynKVaRW5iWxoPfMxHegFJR9MyfpjKeKSyo8Q76HGEfYb3yYdDtWkxHyiDOiASSeusWTFuq473pnhAK8cc0NAc7wWHEIEYsYhOHBxMSXkzk7T5xt23NcElJc6cKEpk8k75T9WiF4aehi1ogqoGG4d1LVoG7cCtmJFN7xLnimsGUIkiQMHa9x1foCA0D4QKt3Ov4PmafCx3avWR0Dy7BylCTcZAvQ5eNuqCotnlr5A9jGAxcOvKec80b6BoRqf8RuBrfxYBjGjZUyFJJwzt4jwNVVmlyuyEARsdlfiFFmOvOqRDZm77dDr40H2zD7BjOyRYTjvhLSc1nyMHJi5Pjc1p4S2DaDAIgexsFjwARu3qre5cl5ZoVzzDPtSn0rg7iKP5BiFOTifD08k1iyJt4vJHK3GYz7v2V0gEI,rhTYC949IWpy0ZMQ2a5Fo71ctF0vTt4n9hVJkPJ7Sm672y2SfqswW4cZEsxhBBRyVPcoZW7eUF1M4ZpWPj0i3Cg7GHbF5JPOQmsULeki8AqXdoc1mmSxJZmFbqKa7uj8yyuZZ1IPmK08FnGaM2EgDj3PN11dT9o34BJ7P73281SEjIy0XiS4ky1o4DXWKK7usnwv1hgsjyTTkzgCz9xhP2TsDRan8Tj8qECDweZzLttZmpNlKxpXnVSOxpbdVuZr,byH2AxyDdrmUoJOYZHK4z0Pzr4UbTwfAIZyQA3ckPdSbgRcFM2U5Pkm3NqwP5XBtWR5nmc2dTGNRkg7wmEqGLymQckGypWVNSpQQbbvFAqIxhpianftih26Ko6uSAgdnYTOYFG1C4gqzUL71hAv7DhEkBGfYIfMYVXBgGQny2PRa5dECgPMX3QgusX2cV4BqQxdwE3Sw1JS9zfvsJOFdsNaPJOcRYv49MmeO0DN4gqKOmvwe2mT3ePa6lT9bjaZ,3,nCjSyurF8LFTfJiJLUsXQDQ810kyHitIvMcq0tkOgNPN1fjnQDV9wlFQTz1NxaXVcxQlAQfFJHyqR3WAWU53vUU2diNOVaSWzhHJJ0EJKbwygpSWXUPNG8fI0RtHjHJmMSmNDxlCaAz7hoAK4I8miH2VhHgzjEszUZ7a6gMjWDFlI36n5zH5s5Rqmgq6GUPlbngBZQNPt2z1YztVEs8Exno96wVu6zkeNDLzm19UzTsNBy2x83o0bP0Ty6NNkSJx,qmAOp1p82PX3YJiO3s6ii79M2P1qocz3DzU9yUb99VN7mRVOSfQCE4DVJJtzkfzflIgGZqGR9tuCy3GtQpoYreG1p1FyeZ8pISYnwjLnDnww4ACumvXXJVtrdKqR4tDOW1SztBXJXpkNGaOsIlQ04gYWRJuOnvSxLCEwmreMDs9uYOyv3qommocM0yVhvY6GWHTVqYPKdyub8a5Fc3X0Pcpd8Ozc8NIiKVeJkxZqFsTPjE2TAqnNrKMdjdku7TNB,UlajiuqnGQyWW9zfRcS4itVm4rqYklrKlVyy5Wbuf90Be5SZBLqNpQdqKVMXE6D1G3ZrotmcjW67d1LjswqAg14uK41Z5mSjaUPqVdjf2ZoLJkkVGYY9xlcVlZIJESYYEcA3vLCzHrogSeHqw5zlqiWbPpuSMwIw6RXxfvY9v978L5kuFcwyr77JNJ3PgXmGyW7QUJ2hAcwW3OCZQN59kfC21lIcA8QUqfuc9ht5dclGMOS0RLg7RP2CgN4q84xF,Js85Un5wVb49S4IIBmAyoS5iJiznI7JDHTnink7e1Lq7gyMruVJZMgk2TAKnN9MztfMoM3WaK2uIXxBsoQ0K5wuNNsHsZnAF3RyxhULlEmHNmz07rLaBoP35oEbXPXT5KjVgzpjcDhejHw6yL0vuyIRz0tHriGOzTScD3JYbU12cANy3CBHV3Ng3Ra7YhD8LO4NQE7QkU4lqeoarlluuEBEVoUVeA1JdGZsTRpIL3e1iR6eTv8mprIRb8OK5YRt,h,Bo01XiUM53XOIc6gP1bjjDYTzLFhGaN9Z4e2h38H3axtBVftaYW2NPCIvJ9GNXU3qaXXym5sqieWtNObKwmgk1GgL9A7LGJCS0nmAogfKrNKveka35g31lDl62LzjT3wzgTi9cprBnwXZbFy4HTrZS3ygd9wGq8CTZllmi7bIAqPFLANECT72LSVEUtNDgjj0zztVwqEWZJfr2OgjabBPQQfjMcvOfCEd8CNCRYQfjKXBMXMpbP03Nn9UC8uPXKg,argeueIipdRqZGnL4mikJhcYNYak2Eu1P0a1igPhKt1wFb20RI88dDCOv7hMDyTyAV9NOaAODT8IJjL6rrUfRnR405QN7BlYrsNajqsiUcJVqJ7eagUajc4mg6SHqwq4TW682MUBfmlTYcGC5m6K2mQdSAjCoCCsnaF7PhCTXRAhOx9tRLBH0XLkEB1YiAmgsKTTPPAo4ppTXpbHlESy590Y88qmLZxmhfHOXoNeMC8cBODSbpEar2EGJZkha6cT,2ohYgEHxGQdWPs0Mk1neQ1x33OcmD4vRomONrAlcF4SpNf9M96r18oshXy8DTY4vqWJSD9PeL04wgPyiLF67HOv7eOTpOZgu4WeulFhc5osWUR4vBCOBReouDQ8BmKG0PUwK5KE5GEMgo9qsTjnF21iBdHU3pwtFB2NBikyoV0w9JBemf3BGQUjHKiluCLOycnb991pNfVWyjCG2QeZEqSj5qPEUwGjBt6t5AMqMveiEpp3sYjb8iK1hrmSZWfo6myUCRFVqkh5c2fVOtWv88fwabSvmo08fvN4IZWTfwQd3t6pUE5Yn3H7mbfxgei5OdjsbjHPzEUZnk92VnEiXB4VOVw7c2mZmvCIcEjvD6v1v0xBUXcqhbFvtsD9caq9drRQtZngfZr09qwbHCsyafaNgynuxkzsSO9IHijiA9PiAvjAjqyI4qKsMDXNr6CG4UBGg1qkwThIqaOe1HPdjlspVyzUjhh9JDsqPzbI5VcmIzBhKdT2II87T6mgiwLG,9,eImpucZsVQ47ULUMULOAGxHsnvZQL04rhMDnKTauxLP96qSxvIRmCEMnOmydDmSDHXmnuMVKWqVC22ZOIrgh1GGyJKGEWnXcJ6hWfnlZ9qmvPF5aLAdCQlLC8cUPq4nM2BXA6ZRIMcUFpEZ8qyHGInUc4J8K3pMos5uZw31ZPkrVKo9tqxSmIGeUaSdgQybT1mo8SPr95dst7UnZf63mDxc5tNj3hm57uVzz5VGG8QlrlSCyd0vPbJeUaszBhjLgz4jguLIvx53KNBlb2GhSXpp8IpizJSVZh46aPHYIFPDp65PsQ0RgzHGdOePtyR05mWXSQ36DlPERLlMz5P5jl91gDI7Zc2908kq8NkoncOrIFVRItUyzh8z539JLe2uViQtcSWqBq14YJ1Ykp7FIFMD7ZpTJA1rJR0s9pBOZ7duZjfWP2UeNQyb6IOmA1OtmQi89lQtDCd5d4ovA1jULWfyr6PLdtEIyEp1SN6Qc1DRRWUaHrZe3DoAyDQyDqy85,B8VXIUj1efCpXj9K3uhLpuJ3QQi7qgjOtR6VMA5C7QVBKaTyAjhHpem3Okee9VJEl3tXEHaDLg1qrWWk5xuD6e0gZlwSTu9bx9RWvf3rqlabgIHnpTDDySfVXHem572EjGLzQAtXb81HPz80ekWEqxzoyrVcwr6WDo1HPHpgo2Pq4CzllZrdl3S1Vb4DxO0P70EvYYsjq7yIRzbgiaChJc59B1AprR49rew4av6VNBK4JN2eAzXulyQcrHyO7kz2,qH4yVrQJkukFU8y04PpU9p4PDXInUleIif3mgPDw9mlhQIS4kdgiyqmepDwaOipe2F4o9yv2JqV4NI7Q51mNDv6zjvWR4kT2J13nzR1LRCsVAErVepI5mQwKyu51PL8facIL1J93nVlG0sMum2asiwENoBZu2DZbKwrBQ3D7sHS6fc8MxhaPmhTIW57vkiHUC9rWl0TBb2MJymJVXKXFfOI0bAiAxw6af19BgDwPT5z4RhDe5YZ8HRIugPyLVJ6,2,IUtjMlpWq3IY1htm3cG7TPMLeGc19nomQRXp8FbSbe4GF6HHPz8SClcMFYZBBP27SXG99YRupSM10fgMT0aedA1kun3spl36fIIV3bCSazIbJ7biu8bvouuKocxELI6pAvIR0KxTqqJ8f0U14ghFV8GMbAKuY6AhPCjdxMEHr1uGIlrOieYs4czfOh70ydk3NF03pvXkGNjqy03taf5Wxd4bzE06nWiktASkeWDIQUlvP5IDgP1SnqiijoLG7CZP,PbVzbeXNqPAeU1V1NFhDrKlgnWhuOLYG4GAXjCqCKZS9IQxBpOZgd6aeE6mnnywjcE0elu4woI0by6pD6qie2fSZ835HgHfj7sV9S82HWbtbYyyuxChZhGxJJu9siolK8a6BkIPq72gCv061bj2vIOzfqiy435R7vx7CRjETAF0eMGW5sR5id7Fvs483oyiWWmzxn4CkkyBQyhk3QmwoEJZteusjFHysxKSKULgiasH6HVNsTnyLuKZ8YMtoEAsV,QRG9c5lTEjiHebhdzFDCSh8gj01qWh1jpesxKmrsSFtewRPPFgasDGMyBzro5xdHeNWyvYe4oA2nIjSm220PNxE3AVRSmDAkcwEE7pDemM1jsY2Voc8JwZIar5SpAidqphJ1AHS8HwpLdwVRf0EQiiiWj5xzwM4OsLixWCWy6adfwmF1RapQuA77A8HLT2TIvu0J39IxlaToSs24KjBFqf2p7cbn8FL1fSiKj7uyQkZg22TQJBwAttZlqCniGzpZ,4oDZ1yDIw4ophaQXm59EKLfQ4kt1Xwm1rvSpakpQhOODdPhNA9E04moGjTCuhsm9FlLI9gj6sb9uxrseAtOVykxc17ZW2eRDw3UA1jb6bMZvbVsQhddUn1tROSJw2jm5d6boWYepBdhNmz0MKckJAIb68w7ryeOvVotGzFzytHh7UQNYCPqZAJoaFAPVqRalmqlkh4TlMB6SWclHSA5n2C2zRaQBMmlR5Jkbu9gIKAisLjk3RXNB6JX8cxMglgh,l,TXLCeoNWLPhoALHV7Vccj6hwxIHKrTBiO8Ir2YX2eadyDc7Nd9VhUrWHTjyXZ27WuAAchIudTe3pnD1NPptoMBwRjgaITjowWfy9sHph4XgwvuVJ8KcAqDrRCBRMq2iAFZeaCBwfQH0SDgtwHwHLDAAQrJ14LJYDZe81PX9D0RCWkbO5DWV9JKVvTHUKi77trr1yP0V1oWLjechkjQ7DzJLEQLw4Hcb8mNWTYZQHxNAjQRDoXtPAKfSpNabTef0vOQIgVWhxhbmAN8gWzBRhO5CzUg7EqPbpBqojv7mqQwOf1XJoPmdFysMyx4cXLaRvbRtcfHsorrPyQpS25tOZiUR6kEW9mAML0NkRftemjpI0C7gqVVXGGAkgB11DzKjAiqAr9QBR2RHxrveIuDI9CfYdD2npT6kQwyU9MK0V70CcJANcPWBHlDiVcAq0Gcu5WAvGca0juE1FBeysoRxPgjs7cl2IXTPuTIKxOyU5f89dBvnDKwgFVmSK4Pg91nnh4UUdBJc9VYUfYp6ZJoGIQa6wAbSOWEgHXet6eEZ0a5Y3ttDawNYKBeVZHdiIXneRi5ej735OGZkglv9bq8cXs9TBzKUNyCTrsfEMkV2kvYMnotqCJpcItv9INUutZHFRlnwBOZCJrFogQJmzZi5SoABGH0PooPO7I41WrrAXKrpyQoPfeikFCfUM8vFz6cexTajfMIWS5HjveNe8ekhG0TgDo4a7hX2djmPp6ds9Mlb0Qjedkw9v11cHYvX0sTS15Yw2e70LFshvmo0k75dqdNhHwEpMPvpmubnCQROGxg9Eq3r9gKwmnTkGcrVf2gy2oko2uYTTzDuz1U0gBTlEP5FMztC2RS2J2eiRwNTkHg5ZUWYFuQrH4Y8nE6gasMsNLZoHb6c6pytNnX4cE3n90KLTcA3wBCvqJB7ne45LqCrd0IGr8LPfxrFWqaKAQY1f4vV1SEjRCYrKlwHqWdAksMc4uvHo2OGC610U4x0Me2xv8eVQd3FcpMzOLKzsTpf1,N7RbJLNRc2nb2g5jsbq2C6ctyWgRQKIkXt9KaKaVPKMwy5jUzdk7pofQ0dY7lQb8t7Fzqke7s23ZEG'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received all data: 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,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,4iwRo9dkgensiSqilYvMv0SXIfTh7pbJw4XK2EF3liltVQsUJNZGqEeuTwfcsUJ6chS5yiizCWjTvpML7L1HvTEwwpp4IpMB9GG4Lk3jhVDQe3F7PrlDtb9LPTx1pXCraphayrzsr8NxlKYlOpuVqkVO6WIArBTelC06OCjPLngFmWVj35WRuSfldLz3lJiEFtlD9u4YNiWLpddETIqkRiHv3gaBbBtQ9C3NKgPzP0MKrVK346oH7mJCOfRHyKbl,rWdRXF3zmYLemFYzCsvpEAGT7NTchW52g4Loh1UQ1ZZJyv8puTNhYjp76Zks7DKypnRwbxGKbTC715PXiE2kXDTx45GWN2pPNm90uefuiqk0Gy8pPjRu9dxLxMmjJY0lev6Y6dGsw31E1OJIYnzMB0Dth2D5LqfMDyUTq8CEjgDOQs39DAFQe2fNB8y6wUfqCjMZ8VVuYLAxesGDNU5nIawWyyOp6B7MYVwQP7GZhO7Oan4sh3b29KscThwJKxb8,2JGl2BQzvIqf7Gjca30RmHRsyPAkiTuOaCRLa49oRdsjKFHtstYfPwdU1NNMojyhMETOYXLG9d413qE2KG9tJtwKpEoOBkcCDYNtV3tD5wf1rubG8P6OgSNm2PeG1Tg8VSlnaUOwE8jXqc8eP6UEqSAI9DzyjPQUnFPz2q5PefK7LXPivNzEs2YiptOYPj1lXii0o4iU5E2dP9fDyimuk88lttF7bghO8TUgIIIqIOksEam6nnCyKD1Fmrm8cIOp,W103uK41DqzPNvRFermHBV8imPJgezssqrMCSMdSwBkd2NZm8hrfskcx7h1FFI6HGUlCEK7uULWijg7eBvc4ETOnhhQ1R0KTMSuMMUoSyraeWrq6vB2PM2cq7KFabxp408MbTc1nbWfr9smdQg8xRmU0XaHS3uOVt9yG94zARLwhetaGNLxxc86KqM3mrT2EvNj3xeiG7mlqdy7KSRKggdMU04nypPoHODqY9hMDxO75ai1cUdcsdvcJNSdKp0Xa,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ldctW05XpuSwjRq9EKmpJwuwr5ACOk1RuzbjCEWslFP1ZY0gszoSPUGLynLt2bcs5CeG6NKGnz5czmaADQhcsoDIsFoAQcHLnEPRwnbazmHa5nUW1cr4Wp3pGOZGCBo2ecXO2K5u5pzWn9XjuiCP8uWyDiA5E5LhMNmunHvmmTqpBpMM4HdF3bGWB37gnMqnyubi4Emowo2tnLIse9IVa5jGo7jtvq8NgNoWLZGw8JvMjRR5TPY0MThhnH81OP7F,Jpq3ZYw7Cdj8TUwZcSPmYqcakLNwjg9vU1Y8rL1QNnCrfHgUsrrewvtkj4Zz0JzXOPzsZm9yXrJt459zvjqnaBxbuNd3qLURloQ7WqdN4cxl5QPzg8pB3CV6VkNBbV3kVoLamxyX569sg8sKPiZMERJTa2lgGkCMokVQqbjsUQDbBrGX6RNVJxRWnq4js195jOq8MNjvB4DxBOcBdcQmKUJsbzYidvOQxuKv7nwKkm66OP6R6vzxeiJJoqxUHrtt,U69jclSBslZtGU7qKc2cXSRRPnA4Ulb44Bd0Fy65DzGBVgR4xY7BizfRnV4X6QBCmfaB9RhkQSthrc20DRmEYzsLoVKZnUAv2UTsr26Isz37uTj3gXAfSKlx1YU0LOQV4CiseHzCFjFhID095wUGRjYYHDEeobn00SCG8QgQGgTYaGz2P8SEcwDHbS1ykEPIQBbsqx2rgaACtEnKibjyeQVy8JG6pbPfdqWukOsbWaD2KRLGQX2nUQJ1iGsQlb5U,7TVL6Yo08aj5VYDNntlZ7SkUWwxKLazq7zhwBvOjWi06RseDSobJoqSglixFAvj8T0hR3EtA5F35E2ZN5qzC5PH7zeQ2mQzZPKrjrCK900rr03dSHJ2Ry8ib316vFNvfJzHIo7xDZiXO5xaaIoaLQC9HjsLqGPhcljt15HeFzoSn7PYEOjLmgGnRLgc5MX8TPj25j7CSLvIWDNKP28Dt2Z8TabDB8s5y5kY4xI769GwPe1SLwAyHEShfkon3RYw3,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [4, 5]
,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'
2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 07:57:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56802
,2017-07-21 07:57:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mEqK5PPv6lziVtZBvLPAuDl44ovf1L3s","error":null,"portNumber":56802}'
,2017-07-21 07:57:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mEqK5PPv6lziVtZBvLPAuDl44ovf1L3s', error: 'null', listeningPort: '56802''
,Connecting to the localhost:56802
,Connecting to the localhost:56802
,Connecting to the localhost:56802
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,Connected to the localhost:56802
,Connected to the localhost:56802
,Connected to the localhost:56802
,ok 91 correct string length
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 92 correct string length
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 07:57:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 7, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 94 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [4, 8, 9]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Advertiser: session connected Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8E00E207-5950-4376-909C-85C20E020EAA state: notConnected -> connecting
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8E00E207-5950-4376-909C-85C20E020EAA
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E00E207-5950-4376-909C-85C20E020EAA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Session.startOutputStream(with:) peer:8E00E207-5950-4376-909C-85C20E020EAA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Session.startOutputStream(with:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [4, 8, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Session.startOutputStream(with:) peer:8E00E207-5950-4376-909C-85C20E020EAA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 8, 9, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1379 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1125 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (4593 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [4, 8, 9, 11, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [4, 8, 9, 12]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received (5505 bytes):'
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [4, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 07:57:51 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4, 8]
,# teardown
,2017-07-21 07:57:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:57:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18629558-6C03-4C79-916D-F,3DF313B891E
2017-07-21 07:57:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:57:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:C67E6215-DEE9-4444-A445-F329D8DE911F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56802
[ThaliCore] Session.disconnect() p,eer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] Session.session(_:peer:didChange:) peer:8E00E207-5950-4376-909C-85C20E020EAA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B,891E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8E00E207-595,0-4376-909C-85C20E020EAA
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0587F97-3B41-4A1E-AC81-C75AB18C12AC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "18629558-6C03-4C79-916D-F3DF313B891E", generation: 0)
,[ThaliCore] Session.deinit peer:8E00E207-5950-4376-909C-85C20E020EAA
[ThaliCore] Session.deinit peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-,07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:57:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:25BA6BBB-1122-4518-BE28-A26BE6496CE8
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E092C709-FCA2-4A63-AB10-BBD04D919050
,[ThaliCore] Browser.startListening
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:57:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:57:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C67E6215-DEE9-4444-A445-F329D8DE911F","generation":0}'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C67E6215-DEE9-4444-A445-F329D8DE911F (syncValue: ODQgnfhc3wanILbyNXFjXJqf3DmO7Edr)'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","generation":0}'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B84EE5A7-220B-4B6A-9E36-00A6615627EF","generation":0}'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","generation":0}'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25BA6BBB-1122-4518-BE28-A26BE6496CE8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25BA6BBB-1122-4518-BE28-A26BE6496CE8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,7E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C67E6215-DEE9-4444-A445-F329D8DE911F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:58:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ODQgnfhc3wanILbyNXFjXJqf3DmO7Edr","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:58:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ODQgnfhc3wanILbyNXFjXJqf3DmO7Edr', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:58:01 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"C67E6215-DEE9-4444-A445-F329D8DE911F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:58:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C67E6215-DEE9-4444-A445-F329D8DE911F","peerAvailable":true,"portNumber":null,"recreate,d":true}'
,2017-07-21 07:58:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:58:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 950874DD-50F5-4754-B6B8-316A63E92A54 (syncValue: sT0CK3GUmjO1DKxnFuL95oHkAFF8Tgk0)'
,2017-07-21 07:58:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C67E6215-DEE9-4444-A445-F329D8DE911F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,0874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,50874DD-50F5-4754-B6B8-316A63E92A54", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,0874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,50874DD-50F5-4754-B6B8-316A63E92A54", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,0874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,50874DD-50F5-4754-B6B8-316A63E92A54", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:950874DD-50F5-4754-B6B8-316A63E92A54:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,0874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:950874DD,-50F5-4754-B6B8-316A63E92A54 error: max retries exceeded
2017-07-21 07:58:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sT0CK3GUmjO1DKxnFuL95oHkAFF8Tgk0","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 07:58:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sT0CK3GUmjO1DKxnFuL95oHkAFF8Tgk0', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 07:58:12 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 07:58:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"950874DD-50F5-4754-B6B8-316A63E92A54","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 07:58:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 07:58:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B84EE5A7-220B-4B6A-9E36-00A6615627EF (syncValue: A8Ql3OD,129Hphuj3q5WyQmhFit7IyJOt)'
2017-07-21 07:58:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B84EE5A7-220B,-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:950874DD-50F5-4754-B6B8-316A63E92A54:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "950874DD-50F5-4754-B6B8-316A63E92A54", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56827
2017-07-21 07:58:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"A8Ql3OD129Hphuj3q5WyQmhFit7IyJOt",,"error":null,"portNumber":56827}'
2017-07-21 07:58:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'A8Ql3OD129Hphuj3q5WyQmhFit7IyJOt', error: 'null', listeningPort: '56827''
,Connecting to the localhost:56827
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 8, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:56827
,2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 07:58:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [4, 8]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,2017-07-21 07:58:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:25BA6BBB-1122-4518-BE28-A26BE6496CE8
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56827
[ThaliCore] Session.disconnect() p,eer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45972DD7-E306-4909-AA0D-0C667C726D62
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70B04368-0D4A-4A8D-9826-F72B55687508
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:58:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","generation":0}'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB (syncValue: quXyzPU9yTRPNUysK3FT2rFqzYEVCmYa)'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B84EE5A7-220B-4B6A-9E36-00A6615627EF","generation":0}'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45972DD7-E306-4909-AA0D-0C667C726D62:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B84EE5A7-220B-4B6A-9E36-00A6615627EF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B84EE5A7-220B-4B6A-9E36-00A6615627EF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9D,B02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
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
[ThaliCore] Session.disconnect() peer:9D,B02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:58:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"quXyzPU9yTRPNUysK3FT2rFqzYEVCmYa","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:58:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'quXyzPU9yTRPNUysK3FT2rFqzYEVCmYa', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:58:27 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:58:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:58:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:58:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:58:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C (syncValue: ph4vtUj9st0MpVMc4oR2N7y,Doq6bYibD)'
2017-07-21 07:58:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0484139D-6BA0-4F9E-B15D-5ACBC,FFF6C4C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9DB02CB4-9A8D-4C90-9B9F-22F0835DE8FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
[ThaliCore] Advertiser: session connected Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
[ThaliCore] Session.startOutputStream(with:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [4, 8, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received (39936 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] Session.session(_:peer:didChange:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56841
,2017-07-21 07:58:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ph4vtUj9st0MpVMc4oR2N7yDoq6bYibD","error":null,"portNumber":56841}'
,2017-07-21 07:58:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ph4vtUj9st0MpVMc4oR2N7yDoq6bYibD', error: 'null', listeningPort: '56841''
,Connecting to the localhost:56841
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,Connected to the localhost:56841
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 07:58:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 8, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [4, 8, 15]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,2017-07-21 07:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] Session.session(_:peer:didChange:) peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "45972DD7-E306-4909-AA0D-0C667C726D62", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45972DD7-E306-4909-AA0D-0C667C726D62
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56841
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ph4vtUj9st0MpVMc4oR2N7yDoq6bYibD","error":"Session disconnected","portNumber":null}'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5AAAA916-5F4F-44CC-BB4E-86FB7B6F4535
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:91174639-A695-43E4-A872-9EE5202B7D86
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A567840-BD3A-492A-B7C1-9FDC148793B0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8A567840-BD,3A-492A-B7C1-9FDC148793B0
,2017-07-21 07:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:58:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
2017-07-21 07:58:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}]'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
,2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}]'
,2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}'
,2017-07-21 07:58:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
2017-07-21 07:58:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}]'
2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}'
2017-07-21 07:58:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A567840-BD3A-492A-B7C1-9FDC148793B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A567840-BD3A-492A-B7C1-9FDC148793B0", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C", generation: 0)
2017-07-21 07:58:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}]'
2017-07-21 07:58:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0484139D-6BA0-4F9E-B15D-5ACBCFFF6C4C","generation":0}'
2017-07-21 07:58:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,07:58:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8A567840-BD3A-492A-B7C1-9,FDC148793B0
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BFE9EB74-B288-401F-9D7D-F1F38D39637E
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20F2AD7F-7475-4D62-AB34-C61D192525BF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:20F2AD7F-7475-4D62-AB34-C61D,192525BF
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopA,dvertising() peerID:20F2AD7F-7475-4D62-AB34-C61D192525BF
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
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
,2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 07:58:48 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 07:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:f552965e-364d-4af9-892c-db9b8d480e23 error: startListeningNotActive
2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"Sz7dK9XJrprejCDqSUKnLpzZA2QiykhY","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"f552965e-364d-4af9-892c-db9b8d480e23","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"f552965e-364d-4af9-892c-db9b8d480e23","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:58:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BE19EC43-145E-4ED5-A051-622E4CDD7A74
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
ok 132 Got null as expected
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"p6tr773tvZJEVCm91MLGqgjSIgQqwkly","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,# teardown
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}]'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}]'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
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
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:51 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0D636CC0-79F4-4D77-9D7B-6067D42B436E
,[ThaliCore] Browser.startListening
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:58:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:1f617dc9-08bc-4ae8-8516-044148fa5955
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:58:53 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6197B4A3-B151-412A-B001-2B3152ED3D6D
2017-07-21 0,7:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D07FD79-57E1-471E-97EA-F0DA589A7F8A
[ThaliCore] Browser.startListening
,2017-07-21 07:58:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:58:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 07:58:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
2017-07-21 07:58:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","generation":0}'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9B670379-F421-4B0E-9E50-7194D7F30765 (syncValue: Ng0T1dh4sso6ozn7d5yzADENd3VOhnDb)'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E","generation":0}'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"68CF2D20-4470-42C1-86DD-5C4B66AE0A9A","generation":0}'
2017-07-21 07:58,:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84BF45AB-2C17-4C8C-9041-D9E809F54A9C","generation":0}'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:58:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
[ThaliCore] Advertiser: session connected Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6197B4A3-B151-412A-B001-2B3152ED3D6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
,[ThaliCore] Session.startOutputStream(with:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [4, 8, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B670379-F421-4B0E-9E50-7194D7F30765:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,670379-F421-4B0E-9E50-7194D7F30765:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,B670379-F421-4B0E-9E50-7194D7F30765", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B670379-F421-4B0E-9E50-7194D7F30765", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:59:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ng0T1dh4sso6ozn7d5yzADENd3VOhnDb","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:59:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Ng0T1dh4sso6ozn7d5yzADENd3VOhnDb', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:59:00 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:59:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9B670379-F421-4B0E-9E50-7194D7F30765","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 07:59:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:59:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E (syncValue: YmBp90KmLtGCgnVMJW3oVLhcPRKp1CPX)'
2017-07-21 07:59:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81,FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:59:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9B670379-F421-4B0E-9E50-7194D7F30765:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:68CF2D20-4470-42C1-86DD-5C4B66AE0A9A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "68CF2D20-4470-42C1-86DD-5C4B66AE0A9A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56854
2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YmBp90KmLtGCgnVMJW3oVLhcPRKp1CPX","error":null,"portNumber":56854}'
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YmBp90KmLtGCgnVMJW3oVLhcPRKp1CPX', error: 'null', listeningPort: '56854''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) found active relay
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DBQTVaeo2qGgLJ4lALHIodNlAtYIwYDL","error":null,"portNumber":56854}'
,ok 144 No error
ok 145 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [4, 8, 15, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0) found active relay
,2017-07-21 07:59:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"N3PuFeWuP3o3pK9iOXdxsQ5eJl0Km8J5","error":null,"portNumber":56854}'
ok 147 No error
ok 148 Ports equal
,# teardown
,2017-07-21 07:59:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:6197B4A3-B151-412A-B001-2B3152ED3D6D
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07,:59:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeS,treams() vsID:16
[ThaliCore] BrowserManager.disconnect peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56854
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDi,sconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [4, 8, 15, 17]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] Session.disconnect() peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:17 [4, 8, 15]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 07:59:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-21 07:59:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6197B4A3-B151-412A-B001-2B3152ED3D6D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
[ThaliCore] Advert,iserRelay.deinit
,# teardown
,[ThaliCore] Session.deinit peer:1F183BA9-61EB-48B5-A5AF-21787DC8097F
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 07:59:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
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
,2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 07:59:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'listening 56857'
,ok 149 Should throw
,# teardown
,2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 56859'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 07:59:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 56862'
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
,2017-07-21 07:59:11 - DEBUG createNativeListener: 'listening 56866'
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
2017-07-21 07:59:12 - DEBUG createNativeListener: 'listening 56871'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 07:59:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 07:59:12 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 56875'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'listening 56879'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 56883'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
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
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'listening 56887'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 07:59:14 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
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
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 07:59:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
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
,2017-07-21 07:59:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 56939'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'listening 56943'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:16 - DEBUG createNativeListener: 'Native Server - close'
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
2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 56946'
ok 196 port must be in range
,# teardown
,2017-07-21 07:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:17 - DEBUG createNativeListener: 'listening 56947'
,ok 197 second start should return same port
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'listening 56949'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 07:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:18 - DEBUG createNativeListener: 'Native Server - close'
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
,listening on 56951
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394
2017-07-21 0,7:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1015D93F-E501-4227-8F24-53E16A8BE897
[ThaliCore] Browser.startListening
2017-07-21 07:59:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 07:59:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84BF45AB-2C17-4C8C-9041-D9E809F54A9C","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84BF45AB-2C17-4C8C-9041-D9E809F54A9C (syncValue: OLrgNWUa03HsIc5loGLYZ6uJIxSsiSUd)'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E","generation":0}'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "81FF9BC4-DDD6-493F-9C81-AB9AE97C1F0E", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84BF45AB-2C17-4C8C-9041-D9E809F54A9C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OLrgNWUa03HsIc5loGLYZ6uJIxSsiSUd","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OLrgNWUa03HsIc5loGLYZ6uJIxSsiSUd', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"84BF45AB-2C17-4C8C-9041-D9E809F54A9C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"84BF45AB-2C17-4C8C-9041-D9E809F54A9C","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:23 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A958306-EC3D-44EB-89A8-EA859D70CC56 (syncValue: LRCNzLf0DN5M3ZeG3o3T7r3qIxkKelfS)'
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:59:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:84BF45AB-2C17-4C8C-9041-D9E809F54A9C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748
[ThaliCore] Advertiser: session connected Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56959
2017-07-21 07:59:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LRCNzLf0DN5M3ZeG3o3T7r3qIxkKelfS",,"error":null,"portNumber":56959}'
2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LRCNzLf0DN5M3ZeG3o3T7r3qIxkKelfS', error: 'null', listeningPort: '56959''
,ok 210 should be equal
2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF4A1875-D77B-4930-8496-4BFA2D99D970 (syncValue: b12uqibxxxqtR68RXKdaeYU6xnR7OMZ7)'
2017-07-21 07:59:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:468EE149-B728-47C9-B180-34D960C0F8FA
[ThaliCore] Advertiser: session connected Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:468EE149-B728-47C9-B180-34D960C0F8FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56963
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b12uqibxxxqtR68RXKdaeYU6xnR7OMZ7","error":null,"portNumber":56963}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b12uqibxxxqtR68RXKdaeYU6xnR7OMZ7', error: 'null', listeningPort: '56963''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BE7D46BF-E36C-4CFC-8F1B-0419EE18E394
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56963
,[ThaliCore] Session.disconnect() peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] BrowserManager.disconnect peer:9A958306-EC3D-44EB-89A8-EA859D70CC56
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56959
,[ThaliCore] Session.disconnect() peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:468EE149-B728-47C9-B180-34D960C0F8FA state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:468EE149-B728-47C9-B180-34D960C0F8F,A
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:BF4A1875-D77B-4930-8496-4BFA2D99D970
,2017-07-21 07:59:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[ThaliCore] Session.session(_:peer:didChange:) peer:3B7311B4-200D-479D-8F41-D0B8ECD9B748 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BE7D46BF-E36C-4CFC-8F1B-0419EE18E394", generation: 0)
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectCo,nnectionFailure registered to native'
2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b12uqibxxxqtR68RXKdaeYU6xnR7OMZ7","error":"Session disconnected","portNumber":null}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:468EE149-B728-47C9-B180-34D960C0F8FA
,# Multiple local http requests
,listening on 56965
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 07:59:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BFCB2BCD-C807-439B-8959-5A1DEF10A145
2017-07-21 0,7:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7856DD58-C61B-439F-B37F-134F59E2FFBD
[Tha,liCore] Browser.startListening
,2017-07-21 07:59:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A958306-EC3D-44EB,-89A8-EA859D70CC56:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF4A1875-D77B-4930-8496-4BFA2D99D970, (syncValue: skudXfaCs3ZAEJSdnX9SBeIwJIRU79KO)'
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","generation":0}'
2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFCB2BCD-C807-439B-8959-5A1DEF10A145:0
2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F6,0E","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
2017-07,-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already r,unning test!'
2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation,":0}'
,2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 07:59:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4A1875-D77B-4930-8496-4BFA2D99D970", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 07:59:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"skudXfaCs3ZAEJSdnX9SBeIwJIRU79KO","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 07:59:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'skudXfaCs3ZAEJSdnX9SBeIwJIRU79KO', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 07:59:38 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 07:59:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 07:59:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BF4A1875-D77B-4930-8496-4BFA2D99D970","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 07:59:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 07:59:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A958306-EC3D-44EB-89A8-EA859D70CC56 (syncValue: BfenEJdSyxcv1HBapt58k9H,ZaYZz0Zup)'
2017-07-21 07:59:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A958306-EC3D-44EB-89A8-EA859,D70CC56:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 07:59:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,7:59:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BF4A1875-D77B-4930-8496-4BFA2D99D970:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9A,958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
[ThaliCore] Advertiser: session connected Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
[ThaliCore] Advertiser: session connected Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A958306-EC3D-44EB-89A8-EA859D70CC56", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BfenEJdSyxcv1HBapt58k9HZaYZz0Zup","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BfenEJdSyxcv1HBapt58k9HZaYZz0Zup', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9A958306-EC3D-44EB-89A8-EA859D70CC56","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C7BBE235-3DD4-43E3-BA80-A3BA3281F60E (syncValue: mAS0110Mksvpvzbo8Xfn8sGljTsQdupm)'
,2017-07-21 07:59:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 07:59:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9A958306-EC3D-44EB-89A8-EA859D70CC56:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D
,[ThaliCore] Session.session(_:peer:didChange:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
,[ThaliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56983
2017-07-21 07:59:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mAS0110Mksvpvzbo8Xfn8sGljTsQdupm",,"error":null,"portNumber":56983}'
2017-07-21 07:59:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mAS0110Mksvpvzbo8Xfn8sGljTsQdupm', error: 'null', listeningPort: '56983''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 07:59:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 98432C64-BBE6-47D0-8F65-58905E66E920 (syncValue: WcrkUW3QaOWCDA4SY5aNNS69XNJVfTZ4)'
,2017-07-21 07:59:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56989
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WcrkUW3QaOWCDA4SY5aNNS69XNJVfTZ4","error":null,"portNumber":56989}'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WcrkUW3QaOWCDA4SY5aNNS69XNJVfTZ4', error: 'null', listeningPort: '56989''
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
[ThaliCore] Advertiser.stopAdvertising() peerID:BFCB2BCD-C807-439B-8959-5,A1DEF10A145
2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56983
[ThaliCore] Sessi,on.disconnect() peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
,[ThaliCore] Session.session(_:peer:didChange:) peer:419DC82A-44BA-4B39-B3B6-93BAD8E5056D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BFCB2BCD-C807-439B-8959-5A1DEF10A145", generation: 0)
,[ThaliCore] Session.deinit peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:98432C64-BBE6-47D0-8F65-58905E66E920
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56989
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:98432C64-BBE6-47D0-8F65-58905E66E920:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,2017-07-21 07:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WcrkUW3QaOWCDA4SY5aNNS69XNJVfTZ4","error":"Session disconnected","portNumber":null}'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 07:59:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# #startListeningForAdvertisements should fail if start not called
,[ThaliCore] Session.deinit peer:3E17DEE8-7F8E-4431-9B40-F19C919BA109
[ThaliCore] Session.deinit peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserRelay.deinit
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 56993'
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
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
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
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'listening 56994'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69F27851-64BC-41F5-8491-F38D95ACDF0F
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:52 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
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
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 56995'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0
,[ThaliCore] Advertiser.stopAdvertising() peerID:19BE7CA5-98AA-49C4-B36F-BA31CBC9E5B0
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'listening 56998'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
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
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 07:59:55 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
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
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'listening 56999'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A789AAA-5A9D-4F89-97AD-FF13E214BA0D
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "51651993-9B37-4F25-A527-2E0A3F3F565D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:51651993-9B37-4F25-A527-2E0A3F3F565D
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:51651993-9B37-4F25-A527-2E0A3F3F565D
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 57002'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:391F489C-D7E1-4473-8F30-195AA40EDF21
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "410E029A-791E-413F-BEB3-632F91CA6FCF", genera,tion: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:410E029A-791E-413F-BEB3-632F91CA6FCF
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:410E029A-791E-413F-BEB3-632F91CA6FCF
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'listening 57004'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D328217-78FD-4F66-9E40-E9461708C2E7
,[ThaliCore] Browser.startListening
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6A3976CF-B8AF-40A5-8184-95B423364213", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6A3976CF-B8AF-40A5-8184-95B423364213
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6A3976CF-B8AF-40A5-8184-95B423364213
,2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 07:59:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 07:59:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 07:59:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 07:59:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 07:59:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 07:59:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 07:59:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 07:59:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
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
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:00:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:00:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
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
,2017-07-21 08:00:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:00:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57007'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:43386CB9-4ADC-4F51-8340-55E959BCE8E7
[ThaliCore] Browser.startListening
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57008'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "651B827C-AF08-4073-BBCD-EC28DC8A9557", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:651B827C-AF08-4073-BBCD-EC28DC8A9557
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:00:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:651B827C-AF08-4073-BBCD-EC28DC8A9557
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:03 - DEBUG thaliMobileNativeWrapper: 'listening 57010'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'listening 57011'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1AEED361-0D65-41D9-8D9D-405907C6E04C
[ThaliCore] Browser.st,artListening
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7F47F410-287B-4671-A5D6-8E1FB0E774E8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7F47F410-287B-4671-A5D6-8E1FB0E774E8
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:00:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:00:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:98432C64-BBE6-47D0-8F65-58905E66E920:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "98432C64-BBE6-47D0-8F65-58905E66E920", generation: 0)
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:C7BBE235-3DD4-43E3-BA80-A3BA3281F60E:0
2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C7BBE235-3DD4-43E3-BA80-A3BA3281F60E", generation: 0)
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,# teardown
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}]'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","generation":0}'
,2017-07-21 08:00:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A8CD3A1-17EC-4D75-ACC9-498530804876:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A8CD3A1-17EC-4D75-ACC9-498530804876", generation: 0)
2017-07-21 08:00:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","generation":0}]'
2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","generation":0}'
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7F47F410-287B-4671-A5D6-8E1FB0E774E8
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:00:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'listening 57013'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2661187A-DA12-4EE1-A021-EFD8AC52707F
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7ACAA28D-9E95-4685-A1D8-2D2948F6818A
,2017-07-21 08:00:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:00:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
2017-07-21 08:00:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
2017-07-21 08:00:14 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C09A6A8,E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1 (syncValue: MqXBsyUmC9cseK33sWlbjFcRDvzAjKPL)'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}]'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}'
,2017-07-21 08:00:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:00:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7ACAA28D-9E95-4685-A1D8-2D2948F6818A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7ACAA28D-9E95-4685-A1D8-2D2948F6818A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57017
2017-07-21 08:00:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MqXBsyUmC9cseK33sWlbjFcRDvzAjKPL","error":null,"portNumber":57017}'
,2017-07-21 08:00:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MqXBsyUmC9cseK33sWlbjFcRDvzAjKPL', error: 'null', listeningPort: '57017''
,2017-07-21 08:00:15 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [4, 8, 15, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:16 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:16 - DEBUG testUtils: 'Got end'
ok 283 response body should match testData
ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7ACAA28D-9E95-4685-A1D8-2D2948F6818A
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 08:00:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57017
[ThaliCore] VirtualSocket.closeStr,eams() vsID:18
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] Session.disconnect() peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [4, 8, 15]
[ThaliCore] Session.deinit peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] TCPListener.deinit
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:00:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:00:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:00:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:00:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98432C64-BBE6-47D0-8F65-58905E66E920","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C7BBE235-3DD4-43E3-BA80-A3BA3281F60E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1A8CD3A1-17EC-4D75-ACC9-498530804876","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'listening 57019'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 57020'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1EFDC2F2-10ED-4806-9FC2-197F3F32DB9D
[ThaliCore] Browser.st,artListening
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:9476F58F-47F8-4A4C-A0A0-0319CEDF586F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9476F58F-47F8-4A4C-A0A0-0319CEDF586F", generation: 0)
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}]'
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","generation":0}'
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9476F58F-47F8-4A4C-A0A0-0319CEDF586F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'listening 57021'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44
,[ThaliCore] Advertiser.stopAdvertising() peerID:20C06FA8-3CAC-4D2D-9CD8-D5AEAA8B0A44
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'listening 57024'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
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
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'listening 57025'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:00:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:00:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
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
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0d39fb9d-29f0-4cc4-881c-bfbcd0cf35b4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0d39fb9d-29f0-4cc4-881c-bfbcd0cf35b4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
,ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9265e34d-1576-4d6d-94e2-60626a0b764c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 354 peer should be available
,ok 355 cache contains native peer
,2017-07-21 08:00:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9265e34d-1576-4d6d-94e2-60626a0b764c","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 356 peer should be unavailable
,ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
,ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c314af0e-34bf-46b7-88e0-be0f95460006","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 362 peer should be available
,ok 363 cache contains wifi peer
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c314af0e-34bf-46b7-88e0-be0f95460006","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
,ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c09906ab-ac23-488e-997f-8556d9b01389","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ad280e5-2024-4aed-9a87-e8d0c6629da5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 370 second peer is available
,ok 371 first and second peers are different
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c09906ab-ac23-488e-997f-8556d9b01389","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ad280e5-2024-4aed-9a87-e8d0c6629da5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3d60ad6e-6fe3-4950-8a67-b921c4d02f82","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-21 08:00:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3d60ad6e-6fe3-4950-8a67-b921c4d02f82","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
,ok 378 error should be null
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
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf798b86-bce6-424d-82eb-7c3f2aad52ef","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 386 peer should be available
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bf798b86-bce6-424d-82eb-7c3f2aad52ef","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 387 peer should be available
,ok 388 should store correct generation
,# teardown
,2017-07-21 08:00:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bf798b86-bce6-424d-82eb-7c3f2aad52ef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 57026'
2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f62416e-a330-46a1-ba2b-06b2706de8c8","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f62416e-a330-46a1-ba2b-06b2706de8c8","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f62416e-a330-46a1-ba2b-06b2706de8c8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'listening 57027'
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"91d88d63-fd5c-4197-8ea8-7b50b9f101b5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"91d88d63-fd5c-4197-8ea8-7b50b9f101b5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"153e2888-f17e-47df-bc2c-813b141ece75","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-21 08:00:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"153e2888-f17e-47df-bc2c-813b141ece75","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'listening 57028'
2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"96553f89-3f5b-4205-b847-ab8a5424d0bb","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"002fdb3b-af75-4815-8d29-600c186de4d9","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"002fdb3b-af75-4815-8d29-600c186de4d9","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"002fdb3b-af75-4815-8d29-600c186de4d9","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"002fdb3b-af75-4815-8d29-600c186de4d9","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-21 08:00:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"96553f89-3f5b-4205-b847-ab8a5424d0bb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
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
,2017-07-21 08:00:39 - DEBUG thaliMobileNativeWrapper: 'listening 57029'
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f419b70e-3fd8-4ef4-a436-9f66a4806085","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"614a1cef-f61b-4684-a9c4-6f0315b906e0","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f419b70e-3fd8-4ef4-a436-9f66a4806085","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"614a1cef-f61b-4684-a9c4-6f0315b906e0","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
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
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:00:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5bf7b3c9-dbf0-4da5-843a-13b4e313607d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5bf7b3c9-dbf0-4da5-843a-13b4e313607d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 438 address has not been changed
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5bf7b3c9-dbf0-4da5-843a-13b4e313607d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 439 new port handled correctly
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5bf7b3c9-dbf0-4da5-843a-13b4e313607d","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-21 08:00:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5bf7b3c9-dbf0-4da5-843a-13b4e313607d","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
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
,ok 450 error should be null
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
,ok 457 error should be null
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
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 57030'
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"edecc8da-e952-4c14-b3cb-0c2a5aa23081","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"edecc8da-e952-4c14-b3cb-0c2a5aa23081","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:00:41 - DEBUG thaliMobileNativeWrapper: 'listening 57031'
,2017-07-21 08:00:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83360274-9771-4a18-a790-b52e71773a09","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:83360274-9771-4a18-a790-b52e71773a09
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:00:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83360274-9771-4a18-a790-b52e71773a09","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:00:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:42 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-21 08:00:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
ok 481 error should be null
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
,ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'listening 57032'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC425ACD-046B-4DDF-B7CC-E9767DAD1DB1
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
2017-07-21 08:00:44 - DEBUG t,haliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9bec11f2-0a07-44a2-92d7-71ad158ece75","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4f39f60b-8d31-4d8f-9b7e-c5d2a1c77715","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9bec11f2-0a07-44a2-92d7-71ad158ece75","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:00:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4f39f60b-8d31-4d8f-9b7e-c5d2a1c77715","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:00:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
,2017-07-21 08:00:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'listening 57033'
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"be0c3526-b4c7-445a-92cc-621e52619c06","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 1
,ok 513 2
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aff2ee04-ff25-46d9-ab7a-958f6f77adb6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"be0c3526-b4c7-445a-92cc-621e52619c06","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:00:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"aff2ee04-ff25-46d9-ab7a-958f6f77adb6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:00:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:00:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
,ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:00:45 - DEBUG thaliMobileNativeWrapper: 'listening 57034'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CE14C433-882F-4790-BE2A-EEC0450765EB
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DD5AEE7-8E99-4B80-925A-2130205EC73D
,[ThaliCore] Browser.startListening
,2017-07-21 08:00:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","generation":0}]'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1 (syncValue: 0)'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE14C433-882F-4790-BE2A-EEC0450765EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
2017-07-21 08:00:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","generation":0}]'
2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","generation":0}'
,2017-07-21 08:00:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:00:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}]'
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","generation":0}'
,2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:00:49 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C0,9A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 08:00:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 1AEB318D-F436-4ED2-92B3-8595DFA2FFED (syncValue: 1)'
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:00:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1AEB318D-F436-4ED2-92B3-8595DFA2FFED", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57040
,2017-07-21 08:00:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":57040}'
,2017-07-21 08:00:52 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C39D4A68-9FE6-420E-91C5-1FF6CE30E22A (syncValue: 2)'
,2017-07-21 08:00:52 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1AEB318D-F436-4ED2-92B3-8595DFA2FFED:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [4, 8, 15, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:00:53 - DEBUG testUtils: 'Got response data'
2017-07-21 08:00:53 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Advertiser: session connected Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F5E784E7-3593-443A-B503-E8844F0337E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5E784E7-3593-443A-B503-E8844F0337E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C39D4A68-9FE6-420E-91C5-1FF6CE30E22A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57044
,2017-07-21 08:00:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":57044}'
,[ThaliCore] BrowserManager.disconnect peer:C09A6A8E-EFDE-48EC-84E1-789AFE3A33B1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Session.startOutputStream(with:) peer:F5E784E7-3593-443A-B503-E8844F0337E9
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) pee,r:C39D4A68-9FE6-420E-91C5-1FF6CE30E22A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 8, 15, 19, 20]
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [4, 8, 15, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:00:56 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:00:56 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] Advertiser: session connected Peer(uuid: "CE14C433-882F-4790-BE2A-EEC0450765EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B17D840B-525A-43E7-8097-00BD8B450B10 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
,[ThaliCore] Session.session(_:peer:didChange:) peer:B17D840B-525A-43E7-8097-00BD8B450B10 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] Session.startOutputStream(with:) peer:B17D840B-525A-43E7-8097-00BD8B450B10
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [4, 8, 15, 19, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1AEB318D-F436-4ED2-92B3-8595DFA2FFED","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:01:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C39D4A68-9FE6-420E-91C5-1FF6CE30E22A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CE14C433-882F-4790-BE2A-EEC0450765EB
,2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:01:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:01:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeS,treams() vsID:21
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [4, 8, 15, 19, 20, 22]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [4, 8, 15, 19, 20]
,ok 527 error should be null
,ok 528 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [4, 8, 15, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:19 [4, 8, 15]
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
,ok 533 getConnectionType
,ok 534 getActionType
,ok 535 getActionState
,ok 536 getPskIdentity
,ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
,ok 539 after start
,2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:01:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 clean kill
,ok 543 should be equal
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
ok 595 good enqueue
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
ok 617 2nd good enqueue
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
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 08:01:13 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
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
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 08:01:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 08:01:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
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
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:01:16 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
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
,ok 684 reject reason should be: Could not establish TCP connection
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
ok 693 must return null after successful kill
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
,ok 699 Should be Could not establish TCP connection
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
,2017-07-21 08:01:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 743 bluetooth peer's notification has correct connection type
,ok 744 tcp peer's notification has correct connection type
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:01:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:01:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-21 08:01:34 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 08:01:34 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
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
,ok 765 action should be resolved with NETWORK_PROBLEM error
,ok 766 correct number of requests
,ok 767 correct number of failures
,ok 768 correct final peer state
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
,# teardown
,2017-07-21 08:01:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
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
,ok 794 should be 204
,# teardown
,2017-07-21 08:01:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 805 should be 204
,# teardown
,2017-07-21 08:01:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 08:01:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:01:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 08:01:54 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 08:01:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 08:01:57 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
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
,ok 851 Got error as expected
,# teardown
,2017-07-21 08:01:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:02:01 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:01 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:02:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-21 08:02:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:02:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
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
,2017-07-21 08:02:13 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:02:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 08:02:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:02:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
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
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:02:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'listening 57173'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3BC99E38-DFA3-444D-847D-934C08CEAD4F
[ThaliCore] Browser.startListening
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8
,2017-07-21 08:02:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
2017-07-21 08:02:23 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}]'
2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 3)'
[ThaliCore] BrowserManager.foundP,eerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
2017-07-21 08:02:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
,2017-07-21 08:02:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:02:23 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Advertiser: session connected Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57176
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":57176}'
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 4)'
,2017-07-21 08:02:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [4, 8, 15, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 8, 15, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Advertiser: session connected Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPLis,tener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3,E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID,:25 [4, 8, 15, 23, 24, 25]
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.deinit vsID:23 [4, 8, 15, 24, 25]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [4, 8, 15, 24, 25, 26]
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [4, 8, 15,, 25, 26]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [4, 8, 15, 25, 26, 27]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 08:02:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [4, 8, 15, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [4, 8, 15, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [4, 8, 15, 25, 26, 27, 28, 29, 30]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [4, 8, 15, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [4, 8, 15, 25, 26, 27, 28, 29, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 36]
[ThaliCore] BrowserRelay.didOpenVirt,ualSocketStreamsHandler
,2017-07-21 08:02:28 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:36 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57192
,2017-07-21 08:02:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":57192}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] Session.session(_:peer:didChange:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] VirtualSocket.deinit vsID:37 [4, 8, 15, 25, 26,, 27, 28, 29, 31, 32, 35, 38]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:02:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [4, 8, 15, 25, 26, 27, 28, 29, 31, 32, 35, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [4, 8, 15, 25, 26, 27, 28, 31, 32, 35, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [4, 8, 15, 25, 26, 27, 28, 32, 35, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [4, 8, 15, 25, 26, 27, 28, 32, 35, 39, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [4, 8, 15, 25, 26, 27, 28, 32, 35, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [4, 8, 15, 25, 26, 27, 28, 32, 35, 39, 40, 41, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescript,ion=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliC,ore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed ,by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NS,LocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed,, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [4, 8, 15, 25, 26, 27, 32, 35, 39, 40, 41, 42, 43, 44, 45, 46]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [4, 8, 15, 25, 26, 27, 35, 39, 40, 41, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [4, 8, 15, 25, 26, 27, 39, 40, 41, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [4, 8, 15, 25, 26, 27, 39, 40, 41, 42, 43, 44, 45]
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:26 [4, 8, 15, 25, 27, 39, 40, 41, 42, 43, 44, 45]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [4, 8, 15, 25, 27, 39, 41, 42, 43, 44, 45]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [4, 8, 15, 25, 27, 39, 41, 43, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [4, 8, 15, 25, 27, 39, 41, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisc,onnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:02:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up -1'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up -1  but we are already killed and so we ignored it'
,2017-07-21 08:02:30 - DEBUG thaliReplicationPeerAction: 'Got error in update: 500 socket hang up -1, but we are already killed and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:39 [4, 8, 15, 25, 27, 41, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [4, 8, 15, 25, 27, 43, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [4, 8, 15, 25, 27, 44]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:44 [4, 8, 15, 25, 27]
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FA1EB5BA-D365-4DBE-9591-19F3D61E10A8
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:02:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [4, 8, 15, 25]
,2017-07-21 08:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:02:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 867 passed
,# teardown
,# setup
,# Coordinated replication action test - should throw error when wrong remote db name is provided
,2017-07-21 08:02:31 - DEBUG thaliMobileNativeWrapper: 'listening 57203'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF3F4E8E-43EA-4E8A-B997-DA2DB9722F24
[ThaliCore] Browser.startListening
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A74787B1-5250-4D60-858F-332648519D4E
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [4, 8, 15, 25, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
2017-07-21 08:02:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}]'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","generation":0}'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-,99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAva,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,8 [4, 8, 15, 25, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
ilable":true,"generation":0,",newAddressPort":false}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalize,dFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:4,8
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 5)'
2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":57176}'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [4, 8, 15, 25, 47]
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [4, 8, 15, 25, 47, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 6)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":57192}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [4, 8, 15, 25, 47]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [4, 8, 15, 25, 47, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [4, 8, 15, 25, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 7)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":57192}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 8)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) found active relay
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":57176}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [4, 8, 15, 25, 47, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] VirtualSocket,.init(inputStream:outputStream:) vsID:52 [4, 8, 15, 25, 47, 51, 52]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:51 [4, 8, 15, 25, 47, 52]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStr,eamsHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [4, 8, 15, 25, 47]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted ,socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-21 08:02:32 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 713A7165-53BE-4979-B6FF-1B1C4676AEBF (syncValue: 9)'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] Session.startOutputStream(with:) peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71,3A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
[ThaliCore] Session.startOutputStream(with:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [4, 8, 15, 25, 47, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [4, 8, 15, 25, 47, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [4, 8, 15, 25, 47, 53]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:53
,[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","generation":0}]'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","generation":0}'
,2017-07-21 08:02:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:02:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A74787B1-5250-4D60-858F-332648519D4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4E2EC99-3E16-40AE-8DE9-96503462B65F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FA1EB5BA-D365-4DBE-9591-19F3D61E10A8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] Sessio,n.deinit peer:D48E2020-BCEB-46C0-9637-2F5F95561B8D
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57214
2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":57214}'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7FE17ECE-9559-451B-8C09-89E0B0DFA7BF (syncValue: 10)'
,2017-07-21 08:02:35 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [4, 8, 15, 25, 47, 53, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Advertiser: session connected Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Advertiser: session connected Peer(uuid: "A74787B1-5250-4D60-858F-332648519D4E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] V,irtualSocket.closeStreams() vsID:55
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [4, 8, 15, 25, 47, 53]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [4, 8, 15, 25, 47, 53, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0 state: notConnected -> connecting
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 868 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [4, 8, 15, 25, 47, 53]
,[ThaliCore] Session.session(_:peer:didChange:) peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57192
[ThaliCore] Session.disconnect() peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57176
[ThaliCore] Session.disconnect() peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConne,cted fire notification for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Session disconnected","portNumber":null}'
[ThaliCore] TCPListener.deinit
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:36 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:36 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-21 08:02:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57218
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":57218}'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 11)'
,2017-07-21 08:02:39 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [4, 8, 15, 25, 47, 53, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Session.startOutputStream(with:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [4, 8, 15, 25, 47, 53, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Session.startOutputStream(with:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [4, 8, 15, 25, 47, 53, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [4, 8, 15, 25, 47, 53, 57, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] Session.startOutputStream(with:) peer:E2806D10-630D-4F19-A090-FDA0F3CE6A37
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [4, 8, 15, 25, 47, 53, 57, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:57 [4, 8, 15, 25, 47, 53, 59, 60]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [4, 8, 15, 25, 47, 53, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [4, 8, 15, 25, 47, 53, 60, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
,[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [4, 8, 15, 25, 47, 53, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_,:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
[ThaliCore] Session.startOutputStream(with:) peer:07228FCA-DEF9-4E7F-95C3-638A9B94BF6A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [4, 8, 15, 25, 47, 53, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  404 no_db_file'
,2017-07-21 08:02:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: no_db_file  and it caused us to complete'
,ok 869 error should be 'no_db_file'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [4, 8, 15, 25, 47, 53, 62]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [4, 8, 15, 25, 47, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57218
[ThaliCore] Session.disconnect() peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7FE17ECE-9559-451B-8C09-89E0B0DFA7BF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7FE17ECE-9559-451B-8C09-89E0B0DFA7BF", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:02:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","generation":0}]'
,2017-07-21 08:02:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","generation":0}'
,2017-07-21 08:02:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:02:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7FE17ECE-9559-451B-8C09-89E0B0DFA7BF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:798FE329-CA2C-48EB-8C64-3BEA2692A145:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,2017-07-21 08:02:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}]'
,2017-07-21 08:02:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","generation":0}'
,2017-07-21 08:02:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 08:02:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:72759949,-905B-4F26-99D5-EC97C00BEAC3 error: max retries exceeded
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Connection could not be established","portNumber":null}'
2017-07-21 08:02:49 - DEBUG thaliMob,ileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Received peer avai,lability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event w,ith {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4,F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 12)'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", g,eneration: 0)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Peer is unavailable","portNumber":null}'
2017-07-,21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 798FE,329-CA2C-48EB-8C64-3BEA2692A145 (syncValue: 13)'
2017-07-21 08:02:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "798FE329-CA2C-48EB-8C64-3BEA2692A145", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":"Peer is unavailable","portNumber":null}'
2017-07-,21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:02:50 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 72759,949-905B-4F26-99D5-EC97C00BEAC3 (syncValue: 14)'
2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:02:50 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,2017-07-21 08:02:50 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 08:02:50 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:02:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"798FE329-CA2C-48EB-8C64-3BEA2692A145","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,2759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:72,759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "72759949-905B-4F26-99D5-EC97C00BEAC3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:72759949,-905B-4F26-99D5-EC97C00BEAC3 error: max retries exceeded
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":"Connection could not be established","portNumber":null}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A74787B1-5250-4D60-858F-332648519D4E
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Session.deinit peer:72759949-905B-4F26-99D5-EC97C00BEAC3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:798FE329-CA2C-48EB-8C64-3BEA2692A145
,[ThaliCore] BrowserManager.disconnect peer:798FE329-CA2C-48EB-8C64-3BEA2692A145
,2017-07-21 08:03:01 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:03:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:03:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"72759949-905B-4F26-99D5-EC97C00BEAC3","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.disconnect peer:72759949-905B-4F26-99D5-EC97C00BEAC3
,[ThaliCore] BrowserManager.disconnect peer:72759949-905B-4F26-99D5-EC97C00BEAC3
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
ok 885 should throw
ok 886 should be equal
ok 887 should be equal
ok 888 should be equal
ok 889 should be equal
,ok 890 (unnamed assert)
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
,2017-07-21 08:03:12 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
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
,ok 951 start before stop
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
,ok 980 start before stop
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
,ok 988 Got socket hang up
,# teardown
,2017-07-21 08:03:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - server always returns 500
,2017-07-21 08:03:20 - DEBUG localSeqManager: 'Got an error trying to update seq []'
,ok 989 Got 500 as expected
,# teardown
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
,ok 999 revs are equal
,# teardown
,2017-07-21 08:03:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - rev got changed under us
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/2,0ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/20ADC4FF-,7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
,2017-07-21 08:03:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict"}'
,ok 1000 Our rev is old so we should fail
,# teardown
,2017-07-21 08:03:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #_doImmediateSeqUpdate - fail if stop is called
,ok 1001 confirm stop caused failure
,(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
,Trace: 
    at $3.prototype.trace@console.js:139:8
    at addListener@events.js:140:1
    at module.exports@/private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.j,s:57:3
    at module.exports/<.start/<@/private/var/containers/Bundle/Application/20ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
    at tryCatcher@/private/var/containers/Bundle/Application/2,0ADC4FF-7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
    at module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/20ADC4FF-,7FB3-4167-B13C-C8DFAAD93E45/ThaliTest.app/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
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
,2017-07-21 08:03:35 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 1007 Expected bad seq error
,# teardown
,2017-07-21 08:03:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #update - do we cancel timer properly on an immediate?
,ok 1008 Different promises
,ok 1009 Timer was cancelled
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
,2017-07-21 08:03:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 08:03:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Coordinated seq test
,2017-07-21 08:03:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:03:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:03:46 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,# setup
,# test thali manager spies
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:46 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 57310'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1737DE26-BD5D-49C4-AC7E-1C8EF148DCF8
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45D0EA1C-6F93-4642-8FBE-8D29B28A5578", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45D0EA1C-6F93-4642-8FBE-8D29B28A5578
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45D0EA1C-6F93-4642-8FBE-8D29B28A5578
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1061 ThaliMobile.stop was called once
,ok 1062 ThaliMobile.stop was called with 0 arguments
,ok 1063 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1064 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1065 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1066 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
,# setup
,# test thali manager multiple starts and stops
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'creating express pouchdb instance'
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
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:47 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'listening 57312'
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:096DA0A6-2AE6-40F8-A957-5919D5C6EC4F
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,2017-07-21 08:03:47 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7462E596-9D5F-43D2-A17D-2270276F17ED", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7462E596-9D5F-43D2-A17D-2270276F17ED
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:03:47 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}]'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:03:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 713A7165-53BE-4979-B6FF-1B1C4676AEBF (syncValue: 15)'
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0) found active relay
,2017-07-21 08:03:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"15","error":null,"portNumber":57214}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
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
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,2017-07-21 08:03:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7462E596-9D5F-43D2-A17D-2270276F17ED
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [4, 8, 15, 25, 47, 53, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] VirtualSocket.handleEventOnOutputStream streams are closed vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [4, 8, 15, 25, 47, 53]
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 1107 ThaliMobile.stop was called once
,ok 1108 ThaliMobile.stop was called with 0 arguments
,ok 1109 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
,ok 1110 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
,ok 1111 ThaliPullReplicationFromNotification.prototype.stop was called once
,ok 1112 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57315'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C79A2371-8504-4D38-A845-CCFC67C3909A
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E10636A-CA7A-4725-8D3A-86FE21D79874", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7E10636A-CA7A-4725-8D3A-86FE21D79874
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7E10636A-CA7A-4725-8D3A-86FE21D79874
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})',
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57317'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:60C404E4-3597-4AF1-9026-45E9DF950079
,[ThaliCore] Browser.startListening
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D594CC7F-5285-4908-854B-85BFD3737DFF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D594CC7F-5285-4908-854B-85BFD3737DFF
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D594CC7F-5285-4908-854B-85BFD3737DFF
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
,2017-07-21 08:03:48 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'starting ThaliMobile'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'listening 57319'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start listening for advertisements'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9D9FFC58-8F1D-4269-AF74-D5AC9DE92849
,[ThaliCore] Browser.startListening
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:713A7165-53BE-4979-B6FF-1B1C4676AEBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "713A7165-53BE-4979-B6FF-1B1C4676AEBF", generation: 0)
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - DEBUG thaliManager: 'start update advertising and listening'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F6E681CC-D96C-4238-B3E8-9F60CDAFE7FF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F6E681CC-D96C-4238-B3E8-9F60CDAFE7FF
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:03:48 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
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
,2017-07-21 08:03:48 - DEBUG thaliManager: 'stopping everything'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F6E681CC-D96C-4238-B3E8-9F60CDAFE7FF
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"networkType":"NATIVE"}})'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}]'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"713A7165-53BE-4979-B6FF-1B1C4676AEBF","generation":0}'
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# teardown
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
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 08:03:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 08:03:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
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
,2017-07-21 08:03:50 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-21 08:03:50 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
